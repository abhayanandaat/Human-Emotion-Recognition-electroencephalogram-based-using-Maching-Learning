# Human-Emotion-Recognition-electroencephalogram-based-using-Maching-Learning


The purpose of this project is to provide an efficient, parametric, general, and completely automatic real time classification method of electroencephalography (EEG) signals obtained from emotions. The particular characteristics of the considered high-frequency signals (theta, alpha, beta, gamma) and adapting strategies like the Fourier Transform, Features Extraction (mean, standard deviation, power) and the K-Neirest Neighbors (KNN) for signal processing, analysis and classification. Moreover, the method is thought to be used in a multi-emotions based Brain Computer Interface (BCI). The proposed method is a two stages algorithm, completely parameterized, aiming at a multi-class classification and may be considered in the framework of machine learning. The first stage, the calibration, is off-line and is devoted at the signal processing, the determination of the features and at the training of a classifier. The second stage, the real-time one, is the test on new data. The FFT is applied to avoid redundancy in the set of features whereas the classification of the selected features, and therefore of the signals, is obtained by the KNN. The average accuracy results are 82.33% (valence) and 87.32% (arousal).


# Required Library

## Python

### Python version 2.7 was used to process EEG data.


1. Numpy

2. Scipy

3. Emokit

4. SocketIO-client

## Node JS

### Node JS was used as GUI.

1. Express JS

2. Socket IO

