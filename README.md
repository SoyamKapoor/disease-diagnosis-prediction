# 📝 Disease Diagnosis Prediction

## 📌 Overview
This Python project predicts diabetes using machine learning on the PIMA Indians Diabetes dataset. It implements Logistic Regression, Random Forest, and Gradient Boosting models, leveraging scikit-learn, pandas, matplotlib, and seaborn. The system identifies key predictors (Glucose, BMI, Age) and achieves an AUC-ROC of 0.83 with Gradient Boosting.

---

## ✨ Features

- **Data Preprocessing**: Handles missing values and normalizes features using StandardScaler.  
- **Model Training**: Implements Logistic Regression, Random Forest, and Gradient Boosting for classification.  
- **Evaluation**: Uses AUC-ROC scores to assess model performance (best: Gradient Boosting, 0.83).  
- **Feature Analysis**: Identifies Glucose (30%), BMI (25%), and Age (20%) as top predictors.  
- **Visualization**: Plots feature importance and ROC curves for insights.  

---

## 🚀 Usage

1. **Load Dataset**: Imports PIMA Indians Diabetes dataset using pandas.  
2. **Preprocess Data**: Normalizes features and handles missing values.  
3. **Exploratory Analysis**: Visualizes correlations and distributions with matplotlib and seaborn.  
4. **Train Models**: Trains and compares Logistic Regression, Random Forest, and Gradient Boosting.  
5. **Evaluate & Visualize**: Computes AUC-ROC scores and plots feature importance/ROC curves.  

---

## 🧰 Dependencies

- Python 3.11  
- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- seaborn  

---

## 📁 Project Structure

```
disease_diagnosis_prediction.ipynb   # Main implementation notebook
README.md                            # Project documentation
```

---

## 📊 Results

Achieves AUC-ROC of 0.83 with Gradient Boosting, identifying Glucose, BMI, and Age as key predictors. Applicable to early diabetes diagnosis and patient risk assessment.

---

## 🔮 Future Improvements

- Explore additional models like XGBoost or SVM for improved accuracy  
- Incorporate hyperparameter tuning for better model performance  
- Expand dataset with more features for enhanced predictions  

---

## 🧠 Top Skills Demonstrated

- Machine Learning  
- Data Preprocessing  
- Data Visualization  
- Python Programming  
- Statistical Analysis  

---

## 🙏 Acknowledgments

- PIMA Indians Diabetes dataset for providing high-quality data  
- scikit-learn for machine learning tools  
- matplotlib and seaborn for visualization capabilities  
