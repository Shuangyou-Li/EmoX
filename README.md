# EmoX1 and EmoX2 Datasets for Emotion Recognition

## Introduction
This repository contains two 14 - channel EEG datasets, EmoX1 and EmoX2, designed for emotion recognition research. The datasets were collected using the Emotiv EPOC X device and include EEG signals from subjects watching emotion - inducing video clips, as well as baseline data and emotion labels.

## Dataset Description

### EmoX1
- **Subjects**: 10 (5 males and 5 females)
- **Stimuli**: 15 emotion - inducing video clips sourced from short - video platforms, reflecting everyday scenarios.
- **Data Format**:
  - **background**: 14×7680
  - **raw signal**: 14×13781 (M)
  - **label**: 3
- **Data Processing**:
  - Sampling rate: 128Hz
  - Filter: Band - pass Hamming sinc linear - phase FIR filter
  - Artifact removal: Artificial Subspace Reconstruction (ASR)

### EmoX2
- **Subjects**: 10 (6 males and 4 females)
- **Stimuli**: 15 emotion - inducing video clips sourced from movie platforms, with a more formal tone.
- **Data Format**:
  - **background**: 14×5760
  - **raw signal**: 14×8891 (M)
  - **label**: 3
- **Data Processing**:
  - Sampling rate: 128Hz
  - Filter: Band - pass Hamming sinc linear - phase FIR filter
  - Artifact removal: Artificial Subspace Reconstruction (ASR)

## Data Collection Process
The data collection process for both datasets is illustrated in Fig. 1. Before each emotion data collection, subjects listened to calming music to return to a neutral emotional state. The EEG signals during this period were recorded as baseline data. After watching the video clips, subjects rated their arousal, valence, and dominance values on a scale from 1 to 5. These ratings were saved as emotion labels in a file named "label.csv".

![image](https://github.com/user-attachments/assets/676bb380-f357-4b22-b3de-57bb2e65805f)


