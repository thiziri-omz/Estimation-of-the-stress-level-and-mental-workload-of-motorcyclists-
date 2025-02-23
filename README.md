# Estimation-of-the-stress-level-and-mental-workload-of-motorcyclists- (Internship project)

The proposed framework uses physiological data, specifically EEG and ECG signals, to evaluate stress levels and mental workload in a driving simulator context. It employs an unsupervised approach that does not require pre-labeled data. Additionally, it is designed to be effective even for studies with short-duration signal recordings. 

The framework follows these steps:

**1- Preprocessing:** EEG and ECG signals are filtered, cleaned, and prepared for feature extraction.  

**2- Feature Extraction:** Metrics indicative of stress and mental workload are extracted, ensuring interpretability even with short recordings.

**3- Analysis:** The evolution of the extracted metrics is analyzed.

**4- Segmentation and Clustering:** Multivariate time series, consisting of the extracted metrics, are segmented and clustered using the TICC (Toeplitz Inverse Covariance-Based Clustering) algorithm. This aims to identify two levels of response related to stress and mental workload.

![Synopsis of the proposed framework.](./schema.png "Synopsis of the proposed framework.")