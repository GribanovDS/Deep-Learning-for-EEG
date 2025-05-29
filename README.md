# Deep Learning For EEG Motor Imagery Classification

## Data availability
The public dataset [BNCI2014_001](https://neurotechx.github.io/moabb/generated/moabb.datasets.BNCI2014_001.html) from the `moabb.datasets` was used for model training and evaluation.

The dataset contain EEG records of 9 volunteers in motor imagery task with the imagination of movement of the left hand (class 1), right hand (class 2), both feet (class 3), and tongue (class 4). Two sessions on different days were recorded for each subject. Each session is comprised of 6 runs separated by short breaks. One run consists of 48 trials (12 for each of the four possible classes), yielding a total of 288 trials per session.

![image](https://github.com/user-attachments/assets/9989a79a-7faa-4dd1-84e7-da2f11485593)

## Models

We used several models: EEGNetLSTM, EEG Conformer and LNN model
The scores on validation sets respectively: 
