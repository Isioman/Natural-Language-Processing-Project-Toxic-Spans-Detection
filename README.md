## Toxic Spans Detection
Rapid growth and increased interaction on social media promoted good awareness and as well caused some damage to society. One major concern is the increase in negative comments and hate speeches posted on social media and online discussion forums. A traditional approach is to identify these harsh comments manually by human moderators and then either filter or remove the comments. This will help promote a safe environment for other users to participate in online discussions. However, the rapid growth in volumes of the data generated on social media and other platforms makes it tedious and complicated for human moderators to identify toxic posts. There is a pressing need to automate the process of annotating such offensive posts. Majority of the currently available toxicity detection datasets and models focus on classifying entire comment or document as toxic. They do not identify the actual sequence of words or toxic spans that actually make the text toxic. This necessity has motivated the SemEval-2021 organizers to design a task called as “Toxic Spans Detection”.

#### Below are the following steps to run the implementation

- Step 1: The full implementation for the system can be found on Google colab. Click on the icon [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Toxic_Spans_Detection.ipynb) to redirect you to the program.

- Step 2: Download the Train, Trial and Test Data files to your Google drive from the "Data" folder.
  <br/>
  <img src="https://github.com/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Images/Downloaddataset.png" width="400" height="400">
  
- Step 3: Ensure that the respective data set file names are same as the respective file names mentioned inside colab.

- Step 4: If it is different, rename the data filenames to match the file names mentioned inside colab.

- Step 5: To download the data to your colab, go to your Google drive and right click on the the "tsd_train.csv" data file. Select "Get link" in the right-click options
<br/>
<img src="https://github.com/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Images/File Right click options.jpg" width="400" height="400">

- Step 6: A new window "Get link" will be opened. Copy the highlighted portion which represents the file id of tsd_train.csv file.
 <br/>
<img src="https://github.com/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Images/File Link - 1.jpg" width="400" height="400">

- Step 7: Paste the copied file id contents in colab file under "Download the train, trial and test data file" section
<br/>
<img src="https://github.com/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Images/Paste the file ID.jpg" width="400" height="400">

- Step 8: Repeat Step 5 for train, trial and test data files
- Step 9: To run the model, change the default settings to GPU
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
