# 🚢 Anomaly Detection in Ship Engine Data
Employing statistical and ML techniques for predictive maintenance using multivariate sensor data.

## 🌟Overview
This project combines statistical and machine learning frameworks to detect anomalous activity in ship engines using real-world sensor data (RPM, fuel pressure, coolant pressure, lubrication metrics). Poorly maintained engines can cause safety risks, fuel inefficiencies, and costly downtime.

## 🎯Objectives
- Preprocess the data and conduct feature engineering.
- Develop and compare statistical and machine learning approaches for anomaly detection.
- Create a pipeline of actionable insights for predictive maintenance.

## 🧠 Techniques Employed
1. **Data proprocessing:** cleaning, outlier handling, and visualisation.
2. **Statistical method:** Interquartile Range (IQR) for anomaly detection.
3. **ML models:** One Class Support Vector Machine (SVM) and Isolation Forest.
4. **Visualisation:** Principal Component Analysis (PCA) for dimensionality reduction and anomaly visualisation in a 2D projection.

## 🔧 Tools
- `Python`
- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `scikit-learn`

## 📊 Results
- By correctly adjusting their hyperparameters, all methods identified a suitable ratio of anomalies within data (between 1%-5%).
- IQR presented some limitations, as it only detects anomalies in individual features, not global anomalies.
- All Isolation Forest models showed consistent results. Hyperparameter tuning of One-Class SVM significantly affect which observtaions were labelled as anomalies.
- PCA visualisations did not provide interpretable insights for stakehoders.

## ➡️ Transferable Applications
The anomaly detection framework has potential applications in different fields:
- **Finance:** Fraud detection.
- **Healthcare:** Early diagnosis.
- **Cibersecurity:** Intrusion detection.
- **Manufacturing:** Predictive maintenance.

## 👨‍💻 Author
Juan Antonio Jiménez Cobo
**LinkedIn:** www.linkedin.com/in/juan-antonio-jiménez-cobo-a16198344
**Email:** juananjico@gmail.com
