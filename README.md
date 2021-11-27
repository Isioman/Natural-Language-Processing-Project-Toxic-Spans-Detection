## Toxic Spans Detection
Rapid growth and increased interaction on social media promoted good awareness and as well caused some damage to society. One major concern is the increase in negative comments and hate speeches posted on social media and online discussion forums. A traditional approach is to identify these harsh comments manually by human moderators and then either filter or remove the comments. This will help promote a safe environment for other users to participate in online discussions. However, the rapid growth in volumes of the data generated on social media and other platforms makes it tedious and complicated for human moderators to identify toxic posts. There is a pressing need to automate the process of annotating such offensive posts. Majority of the currently available toxicity detection datasets and models focus on classifying entire comment or document as toxic. They do not identify the actual sequence of words or toxic spans that actually make the text toxic. This necessity has motivated the SemEval-2021 organizers to design a task called as “Toxic Spans Detection”.


### Cloning the repository
- The full implementation for the system can be found on [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Toxic_Spans_Detection.ipynb)

#### Below are the following steps to run the implementation

- Step 1: Download the Data file to your Google drive.
  <br/>
  <img src="https://github.com/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Images/Downloaddataset.png" width="400" height="400">
  
- Step 2: Ensure that the dataset file name is the same as the filename in the colab file.

- Step 3: if it is different, rename the data filename to match the colab file name. If not, skip to step Four

- Step 4: To download the data to your colab, go to your drive and right click on the the data file, click on link and copy the file id in the link to the colab.
  <br/>
  <img src="https://github.com/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Images/download_data_from_drive_to_colab.png" width="400" height="400">

- Step 5: Apply step 4 to apply to train, test and trial.
- Step 6: To run the model, you can change the default settings to GPU
  <br/>
  <img src="https://github.com/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Images/4.png" width="400" height="400">
  
 #### Side Notes:
 1. A common error that can occur is excedding the allocation of GPU. To solve this:
  - After running the model and analyzing the metrics, ensure you empty cache before rerun the experiments. 
 <br/>
  <img src="https://github.com/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Images/6.png" width="400" height="400">
  
 Another Option is to:
  - Rerun the model by selecting the options in Runtime -> Restart and Run all.
 <br/>
  <img src="https://github.com/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Images/5.png" width="400" height="400">
 2. Other procedures to look out for include:
    - Ensuring the drive is always mounted for easy reading and writing of data.

### Contributions and Questions
#### Contact: Contributors
- Madhu Kumar Dogiparthy | Graduate Student at VCU, Virginia, USA | dogiparthym@vcu.edu
- Goodness Isioma Nwabueze | Graduate Student at VCU, Virginia, USA | nwabuezeg@vcu.edu

We are open to your contributions and questions. 
