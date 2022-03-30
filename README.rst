Speech Emotion Recognition App 

Speech Emotion Recognition (SER) App processes and classifies speech signals to detect the embedded emotions.

Dataset Used : 
--------------

Ryerson Audio-Visual Database of Emotional Speech (Ravdess)

Data Augmentation:
------------------

Methods used for data augmentation :

● Noise injection 
● Stretching
● Shifting
● Pitching


Feature Extraction
--------------------

Features extracted from the data : 

1. The Zero-Crossing Rate (ZCR): The number of times the signal changes value, from positive to negative and vice versa, divided by the length of the frame.

2. RMS: Extracts the Root Mean Square (RMS) from a set of samples.

3. MFCC: Mel-frequency Cepstral coefficients (MFCCs) are the signal coefficients that are collected to forms MFC.
The Mel-frequency cepstrum different from cepstrum in the frequency bands which are equally divided on the Mel scale.



Performance Measure : 92% accuracy achieved on test data 
--------------------------------------------------------



