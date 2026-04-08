# PAACDA - Proximity Based Adamic Adar Corruption Detection Algorithm

PAACDA is a machine learning-based data corruption detection system designed to accurately identify corrupted or anomalous data points in structured datasets using a novel graph-based similarity approach.

Traditional anomaly detection techniques such as Isolation Forest, LOF, and DBSCAN often struggle to distinguish between true outliers and intentionally corrupted data. PAACDA addresses this limitation by leveraging the **Adamic Adar Index** and graph-based proximity analysis to improve corruption detection performance.

## Key Features
- Detects corrupted data with high precision and recall
- Graph-based anomaly detection using modified Adamic Adar similarity
- Outperforms traditional anomaly detection algorithms
- Supports linear and clustered datasets
- GUI-based interface for easy interaction
- Comparative analysis with benchmark ML models

## Proposed Algorithm
### PAACDA (Proximity Based Adamic Adar Corruption Detection Algorithm)
PAACDA is a modified version of the Adamic Adar graph similarity algorithm adapted for corruption detection.

It:
- Converts dataset points into graph representations
- Computes proximity-based similarity between data nodes
- Detects anomalies/corruptions based on abnormal similarity scores
- Flags corrupted entries for further analysis

## Performance

- Clustered Data - 96.35%
- Linear Data - 99.04%

PAACDA outperformed:
- Isolation Forest
- Local Outlier Factor (LOF)
- DBSCAN
- K-Means Clustering
- One-Class SVM


## Tech Stack
- **Programming Language:** Python
- **Frontend / GUI:** Tkinter
- **Backend:** Python
- **Database:** MySQL
- **ORM:** Django ORM
- **Visualization:** Matplotlib
- **ML Libraries:** Scikit-learn, TensorFlow, Keras
- **Data Processing:** Pandas, NumPy, SciPy
