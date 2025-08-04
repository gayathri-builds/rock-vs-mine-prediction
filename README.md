# Rock vs Mine Prediction – Machine Learning Project

## 🧠 Project Overview

This machine learning project aims to classify sonar signals as either **Rock** or **Mine** based on the frequency response of sonar signals bounced off the object. It is built using supervised learning algorithms and trained on the [UCI Sonar dataset](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+sonar+mines+vs.+rocks).


## 📁 Dataset

- **Source:** UCI Machine Learning Repository  
- **Features:** 60 numerical attributes (energy of sonar signal at different frequencies)  
- **Target:** `R` (Rock) or `M` (Mine)


## ⚙️ Tools & Technologies

- **Language:** Python  
- **Libraries:** NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn  
- **Algorithms Used:**  
  - Logistic Regression  
  - Support Vector Machine (SVM)  
  - Random Forest Classifier


## 🔍 Workflow

1. **Data Loading and Exploration**
   - Checked for missing values and data distribution
   - Visualized correlation between features and target

2. **Preprocessing**
   - Label encoding of target variable
   - Feature scaling using StandardScaler

3. **Model Training**
   - Trained Logistic Regression, SVM, and Random Forest models
   - Used train-test split and cross-validation

4. **Evaluation**
   - Compared models using accuracy, precision, recall, F1-score, and confusion matrix


## 📈 Results

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | ~86%     |
| SVM                 | ~90%     |
| Random Forest       | ~92%     |

> ✅ **Random Forest** performed the best among the tested models.


## 📊 Visualizations

- Confusion matrix heatmaps  
- Feature importance (Random Forest)  
- Accuracy comparison bar chart  

