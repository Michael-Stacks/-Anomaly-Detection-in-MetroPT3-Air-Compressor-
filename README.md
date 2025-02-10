🚆 Anomaly Detection in MetroPT3 (Air Compressor)
This project focuses on anomaly detection in air compressor sensor data from the MetroPT3(AirCompressor) dataset.
Using unsupervised learning, we implement two approaches:

Batch processing with IsolationForest.
Streaming simulation with Local Outlier Factor (LOF).
📂 Dataset
The dataset consists of 15 sensor signals (8 digital and 7 analog) recorded at 1Hz from February to August 2020.
These signals include pressure readings, motor current, oil temperature, and various electrical signals.

🏗️ Methodology
IsolationForest detects anomalies by isolating observations through random partitioning.
Local Outlier Factor (LOF) identifies anomalies in a moving time window using nearest neighbors.
📊 Results
The project provides visualizations highlighting detected anomalies, comparing both methods.
Link to the dataset on kaggle: https://www.kaggle.com/datasets/anshtanwar/metro-train-dataset

![TP01_Industrie_4 0 ](https://github.com/user-attachments/assets/324d736a-9ca7-40c3-ac49-ac6bcc4c015a)
