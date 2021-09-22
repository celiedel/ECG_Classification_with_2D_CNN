# ECG_Classification_with_2D_CNN
Classification of ECG heartbeats using images 

Project: This project examines accurately classifying ECG heartbeats with a 2D convolutional neural network using jpeg images. It is loosely based on the paper: ECG arrhythmia classification using a 2-D convolutional neural network - Tae Joon Jun, Hoang Minh Nguyen, Daeyoun Kang, Dohyeun Kim, Daeyoung Kim, Young-Hak Kim  
Link to the paper: https://arxiv.org/abs/1804.06812v1
Traditional machine learning models are also included for comparison. 
See the Architectural Decision Document and the Notebooks for more explanation.

Data: The original dataset is composed of two collections of heartbeat signals derived from two datasets in heartbeat classification, the MIT-BIH Arrhythmia Dataset and The PTB Diagnostic ECG Database. These signals correspond to electrocardiogram (ECG) shapes of heartbeats for normal and abnormal rhythms.  The signals are preprocessed and segmented, with each segment corresponding to a heartbeat. Only (mitbih_train.csv) is used for this project and can be downloaded from Kaggle.

ECG Rhythm Classes:
    0: N - Normal
    1: S - Atrial premature
    2: V - Premature ventricular contraction
    3: F - Fusion of ventricular and normal
    4: Q - Paced Unclassifiable
Dataset Links: https://www.kaggle.com/shayanfazeli/heartbeat?select=mitbih_train.csv
https://www.physionet.org/content/mitdb/1.0.0/
https://www.physionet.org/content/ptbdb/1.0.0/
