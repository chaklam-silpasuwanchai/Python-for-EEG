# Python-For-EEG

Here is a simple repository in which I demonstrate basic analysis on EEG signal.  Topics covered:

Credits:  I got help from my Ph.D. student - Mr. Akraradet (https://github.com/akraradets) on asymmetry and my Master student - Mr. Nutapol (https://github.com/nutapol97) on motor imagery.  

## Topics

**Time-Based** [Datasets:  P300 signal]

1. Event-related potentials and 1-dimensional convolution
2. Long short-term memory

**Frequency-Based** [Datasets:  DEAP and SSVEP]

3. Spectral analysis and alpha asymmetry
4. Canonical correlation analysis

**Component-Based** [Datasets:  Motor Imagery]

1. Event-related desynchronization


## Datasets

All datasets can be downloaded at:  [Google Drive](https://drive.google.com/drive/folders/1q_UbAIP1yPCkIjYCMIaJWG2cBn0K4nfa?usp=sharing) (except the DEAP dataset)

1. P300:  This is my personal P300 signal I acquired through my OpenBCI headset while visually attending to 36 alphabetical targets.  When the flash flickers at the target I am looking at, there will be a signal rise at 300ms after the stimulus onset.   In the dataset, the columns are timestamps (128 samples per second), 16 channels of 'Fp1', 'Fp2', 'F7', 'F3', 'F4', 'F8', 'C3', 'Cz', 'C4', 'T5', 'P3', 'P4', 'T6', 'POz', 'O1', 'O2', and the marker indicating the events.  The marker format will be explained more in the notebook.

2. DEAP dataset:  It's basically a dataset regarding participants watching some 1-min emotional videos while wearing 32 EEG channels.  For more details, read https://www.eecs.qmul.ac.uk/mmv/datasets/deap/

3. SSVEP:  Here we record users looking at three different circles flickering at 6, 10, and 15Hz respectively.  We will be classifying the signals using filterbank canonical correlation analysis.

4. Motor Imagery: Here we record one user performing imagined left and right movements.  We shall explore event-related desynchronization for decoding the classes.
