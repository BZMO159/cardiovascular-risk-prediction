# cardiovascular-risk-prediction
Machine learning project for cardiovascular risk prediction
# Cardiovascular Risk Prediction


##  Project Overview
This project focuses on analyzing and predicting cardiovascular disease risk using patient data.

The goal is to identify key risk factors and build predictive models based on clinical and behavioral variables.

---

##  Dataset
- ~70,000 patients
- Variables:
  - Age, BMI, blood pressure
  - Cholesterol, glucose
  - Lifestyle (smoking, alcohol, activity)
- Target variable: `cardio` (0 = healthy, 1 = disease)

---

##  Methodology

### Data preprocessing
- Removal of outliers
- Feature engineering:
  - BMI
  - Pulse pressure
  - Mean arterial pressure
- Conversion of categorical variables

### Exploratory analysis
- Distribution analysis
- Correlation matrix
- Principal Component Analysis (PCA)

### Unsupervised learning
- K-means clustering
- Hierarchical clustering

### Supervised learning
- Logistic Regression (with stepwise selection)
- Random Forest

---

## Results
- Accuracy ≈ 73%
- Random Forest slightly outperforms Logistic Regression
- Key risk factors identified:
  - Age
  - Blood pressure
  - Cholesterol

---

##  Visualizations

### Correlation matrix
![Correlation](figures/correlation.png)

### PCA
![PCA](figures/pca.png)

### Feature importance (Random Forest)
![Feature Importance](figures/feature_importance.png)

---

##  Conclusion
This project demonstrates how machine learning can be applied to healthcare data to predict cardiovascular risk and identify important clinical factors.

---

##  Authors
- Mohamed Amine Bouaziz  
- Niamatellah Lahkim  

---

## Dataset source
https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset
