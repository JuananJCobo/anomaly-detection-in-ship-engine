# 🚢 Anomaly Detection in Ship Engine Data
Statistical and machine learning techniques for predictive maintenance using multivariate sensor data.

## Overview
This project applies statistical and machine learning frameworks to detect anomalous activity in ship engines using real-world sensor data (RPM, fuel pressure, coolant pressure, and lubrication metrics). Poorly maintained engines can cause safety risks, fuel inefficiencies, and costly downtime.

## Objectives
- Preprocess the data and perform feature engineering to identify meaningful patterns.
- Develop and compare statistical and ML approaches for anomaly detection.
- Build a pipeline of actionable insights for predictive maintenance.

## Techniques Employed
1. **Data preprocessing:** cleaning, outlier handling, and visualisation.
2. **Statistical method:** Interquartile Range (IQR) for anomaly detection.
3. **ML models:** One Class Support Vector Machine (SVM) and Isolation Forest.
4. **Visualisation:** Principal Component Analysis (PCA) for dimensionality reduction and 2D anomaly visualisation.

## Tools
- `Python`
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## Results
- All methods identified a realistic anomaly ratio (1–5%) when properly tuned.
- IQR was effective for univariate detection but limited for multivariate anomalies. 
- Isolation Forest offered stable results across runs.
- One-Class SVM required careful hyperparameter tuning for reliable detection.
- PCA visualisations provided limited interpretability for stakeholders.

## Business Applications
The anomaly detection framework is industry-agnostic, with potential applications in different fields:
- **Finance:** Fraud detection.
- **Healthcare:** Early diagnosis.
- **Cybersecurity:** Intrusion detection.
- **Manufacturing:** Predictive maintenance.

## Licence
This project is licensed under the [MIT License](LICENSE).

## 👨‍💻 Author
**Juan Antonio Jiménez Cobo**  
- [LinkedIn](https://www.linkedin.com/in/juan-antonio-jiménez-cobo)  
- 📧 juananjico@gmail.com
