# UCIHAR_class_prediction_test

I used the raw inertial signals data such as accelerometer and gyrometer data values, from which we train three deep learning algorithms. Further, TSFEL (Time Series Feature Extraction Library) was used to extract all domain features from the dataset. Those features were bulk processed so as to optimize learning. All features, original, TSFEL and extracted, were scaled for smooth processing. 

Algorithms:

DEEP LEARNING : CNN, LSTM, CNN-LSTM on features taken from raw inertial signals data.
MACHINE LEARNING: Random forest, SVM and Logistic Regression on both original 561 features from the UCI HAR dataset and on extracted TSFEL features.
