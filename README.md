# EMG Data Recorded During Emotional Expressions

This repository contains the EMG dataset. You can find the details of the data and the registration method in the publication: 

Kołodziej, Marcin, Andrzej Majkowski, and Marcin Jurczak. 2024. "Acquisition and Analysis of Facial Electromyographic Signals for Emotion Recognition" Sensors 24, no. 15: 4785. https://doi.org/10.3390/s24154785

# Database description
The EMG signals were captured using a g.Tec g.USBAmp 2.0 24bit bioelectrical signal amplifier and g.LADYBIRD series active electrodes, with eight measuring electrodes, a reference electrode (Ref), and a ground electrode (Gnd). The signals were recorded at 4800 Hz, using a high-pass filter of 0.1 Hz, a low-pass filter of 1000 Hz, and a 50 Hz Butterworth 4th-order notch filter. Additional Butterworth notch filters were applied at 100Hz, 150Hz, 200Hz, etc., up to 1000Hz, to remove power grid harmonic disturbances. No other preprocessing methods were applied.

Sixteen male participants (S01–S16) from the Warsaw University of Technology, aged 20 to 57, with an average age of 32.3±13.7 years, consented to participate. They performed specific emotions (joy, sadness, surprise, disgust, anger, and fear) or remained neutral while seated at a desk. For each emotion and the neutral state, ten 1/4-second segments of EMG signal were selected, and average power in the time domain was calculated for each segment and channel.

The dataset includes features of EMG signals for users S01-S02 during facial expressions associated with emotions. The .mat files contain data from 8 electrodes placed as follows: CH1-above the eye, CH2-below the eye, CH3-beside the eye, CH4-forehead, CH5-beside the mouth, CH6-above the mouth beside the nose, CH7-cheek, CH8-jaw. Column 9 indicates the emotion: 1-neutral; 2-smile; 3-sadness; 4-surprise; 5-disgust; 6-anger; 7-fear. Each file contains 70 examples.





