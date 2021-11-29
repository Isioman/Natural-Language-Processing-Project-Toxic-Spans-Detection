## Toxic Spans Detection
Rapid growth and increased interaction on social media promoted good awareness and as well caused some damage to society. One major concern is the increase in negative comments and hate speeches posted on social media and online discussion forums. A traditional approach is to identify these harsh comments manually by human moderators and then either filter or remove the comments. This will help promote a safe environment for other users to participate in online discussions. However, the rapid growth in volumes of the data generated on social media and other platforms makes it tedious and complicated for human moderators to identify toxic posts. There is a pressing need to automate the process of annotating such offensive posts. Majority of the currently available toxicity detection datasets and models focus on classifying entire comment or document as toxic. They do not identify the actual sequence of words or toxic spans that actually make the text toxic. This necessity has motivated the SemEval-2021 organizers to design a task called as “Toxic Spans Detection”.

#### Below are the following steps to run the implementation

- Step 1: The full implementation for the system can be found on Google colab. Click on the icon [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Toxic_Spans_Detection.ipynb) to redirect you to the program.

- Step 2: Download the entire code to your local machine from Github.
 <img src="https://github.com/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Images/Download Code.png" width="500">
  
- Step 3: Ensure that a zip folder with name "Natural-Language-Processing-Project-Toxic-Spans-Detection-main.zip" is downloaded to your local machine.
- Step 4: Open the folder where the zip file is downloaded.
<img src="https://github.com/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Images/Open download folder.jpg" width="450">
- Step 5: Unzip the downloaded folder to retrieve the contained folders.
  * To unzip the folder using command prompt: Click [here](https://linuxize.com/post/how-to-unzip-files-in-linux/) to know more details about installing unzip package in Linux and then execute the unzip command.
  * To unzip the folder from the file explorer window
  <img src="https://github.com/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Images/Extract Here.jpg" width="450">
- Step 6: Ensure that following folders and files are located in the extracted folder.
    <img src="https://github.com/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Images/Contents of folder.jpg" width="450">
- Step 7: Sign in to your Google Drive from the browser. [Google Drive] ("https://www.google.com/drive/")
- Step 8: Upload the data files (tsd_train.csv, tsd_trial.csv and tsd_test.csv) from your local machine (<...>/Natural-Language-Processing-Project-Toxic-Spans-Detection-main/Data) to your Google Drive. 
  * Open your Google Drive, select "My Drive" option and then right-click on it.
  * Select Upload files
<img src="https://github.com/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Images/Upload Files.png" width="450">

- Step 5: Open the directory where the data files are present and select them to upload them to your Google Drive.
<img src="https://github.com/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Images/Data Folder.jpg" width="700" height = "400">

- Step 6: To download the data to your colab, go to your Google drive and right click on the the "tsd_train.csv" data file. Select "Get link" in the right-click options
<img src="https://github.com/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Images/File Right click options.jpg" width="500">

- Step 7: A new window "Get link" will be opened. Copy the highlighted portion which represents the file id of tsd_train.csv file.
<img src="https://github.com/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Images/File Link - 1.jpg" width="500" >

- Step 8: Paste the copied file id contents in colab file under "Download the train, trial and test data file" section
<img src="https://github.com/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Images/Paste the file ID.jpg" width="500">

- Step 9: Repeat Step 5, Step 6 and Step 7 for trial(tsd_trial.csv) and test(tsd_test.csv) data files
- Step 10: To run the model, first change the Runtime type to GPU.
 <br/>
  <img src="https://github.com/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Images/Change run time type-1.jpg" width="600">
  <img src="https://github.com/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Images/Change run time type.jpg" width="400">
  
 - Step 11: Select "Run all" option to execute the code
 <img src="https://github.com/Isioman/Natural-Language-Processing-Project-Toxic-Spans-Detection/blob/main/Images/Run all option.jpg" width="600">
  
 #### Side Notes:
 1. A common error that can occur is excedding the allocation of GPU. To solve this:
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
