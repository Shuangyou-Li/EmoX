Two 14-channel EEG datasets for emotion recognition
EmoX1: The dataset contains EEG signals of 10 subjects (5 males and 5 females), which are collected by a 14 - channel Emotiv EPOC X device while subjects watched 15 emotion stimulus clips. And these signals are stored in folders ending with “raw_signal”. To help subjects return to a neutral emotional state, before each emotion data collection, we play a piece of calming music, and record the EEG signals as baseline data, subsequently which are stored in folders ending with “background.” All EEG signals are recorded at a sampling rate of 128Hz and processed using a band-pass Hamming sinc linear-phase FIR filter. After watching the video clips, subjects are asked to rate the arousal, valence, and dominance values on a scale from 1 to 5. These ratings are saved as emotion labels in a file named “label.csv”. The specific data collection process is illustrated in Fig. 1.
EmoX2: The data collection process and equipment are the same as in EmoX1, with the only difference being the gender composition of the subjects (this time consisting of 6 males and 4 females). Additionally, we selected a different set of 15 emotion stimuli. The stimuli clips in EmoX1 were sourced from short video platforms, reflecting more everyday scenarios, while the EmoX2’s are from movie platforms, giving them a more formal tone.
![image](https://github.com/user-attachments/assets/2ca31640-d037-44a9-a922-6b94cd05bddf)
Fig.1. Data Collection Process of the Dataset
The data format for each trial of the subjects in the two datasets is shown in Table 1.
Table 1. Dataset Description
Datasets	background	raw signal	label
EmoX1	14×7680	14×13781(M)	3
EmoX2	14×5760	14×8891(M)	3
	Declaration: We have made the dataset freely available to the public. If you use this data in your scientific research, please be sure to cite our paper.
