# Python-For-EEG

*Note:  On progress.   Don't fork yet.  Once I have time, I will complete this for good, and will leave this note.*

Here is a simple repository in which I demonstrate how to perform DL modeling on EEG signal.  Topics covered:

## Topics

**Time-Based** 
[Datasets:  P300 signal]
01. 1-dimensional convolution
02. 2-dimensional convolution
03. Long short-term memory

**Frequency-Based** 
[Datasets:  Stress (TBD)]
04. Analyzing alpha, beta, gamma, asymmetry
[Datasets:  SSVEP (TBD)]
05. Canonical correlation analysis

**Component-Based**
[Datasets:  Motor Imagery (TBD)]
06. Common spatial pattern analysis


## Datasets

All datasets can be downloaded at:  [Google Drive](https://drive.google.com/drive/folders/1q_UbAIP1yPCkIjYCMIaJWG2cBn0K4nfa?usp=sharing)

1. P300:  This is my personal P300 signal I acquired through my OpenBCI headset while visually attending to 36 alphabetical targets.  When the flash flickers at the target I am looking at, there will be a signal rise at 300ms after the stimulus onset.   In the dataset, the columns are timestamps (128 samples per second), 16 channels of 'Fp1', 'Fp2', 'F7', 'F3', 'F4', 'F8', 'C3', 'Cz', 'C4', 'T5', 'P3', 'P4', 'T6', 'POz', 'O1', 'O2', and the marker indicating the events.  The marker format will be explained more in the notebook.

2. Stress:  Here we record users resting-state EEG for 10 seconds, in which the label is either subjects suffering from chronic stress or not.  This label was acquired through some clinical stress questionnaires.  Here I shall demonstrate how to use frequency-based analysis to understand stress and non-stressed subjects.

3. SSVEP (TBD)

4. Motor Imagery (TBD)

