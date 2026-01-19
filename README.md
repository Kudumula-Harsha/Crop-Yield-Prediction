# 🌾 Smart Crop Recommendation System

## 📌 Project Overview
The goal of this project is to build a **Smart Crop Recommendation System** using machine learning that suggests the best crop for a farm based on environmental and soil conditions.  
This can help farmers increase yield and reduce crop failure by recommending the most suitable crop type for a given set of features.

---

## 📂 Dataset Information
This project uses the **Smart Crop Recommendation Dataset** sourced from Kaggle.

### 🔗 Dataset Links
- **Smart Crop Recommendation Dataset**(https://www.kaggle.com/datasets/miadul/smart-crop-recommendation-dataset)

- **Direct Data File**(https://www.kaggle.com/datasets/miadul/smart-crop-recommendation-dataset?select=data)

All dataset credits belong to the original Kaggle authors and dataset providers.

---

## 🧠 Problem Statement
The goal is to recommend which crop should be planted given the following soil and environmental features:

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Soil Values
- Temperature
- Humidity
- pH
- Rainfall
- Pesticides, Fertilizers used

This is a **multi-class classification problem** where the model predicts the most suitable crop type based on these features.

---

## ⚙️ Technologies & Tools Used
- **Programming Language:** Python  
- **Libraries:**
  - NumPy
  - Pandas
  - Scikit-learn
  - Matplotlib / Seaborn  
  - Jupyter Notebook

---

## 🔍 Project Workflow
This project follows these key steps:

1. Data Loading & Inspection  
2. Exploratory Data Analysis (EDA)  
   - Feature distribution  
   - Correlation analysis  
3. Data Preprocessing  
   - Missing value handling  
   - Encoding (if needed)  
   - Train/Test split  
4. Model Training & Evaluation  
   - Random Forest Classifier  
   - XGB Classifier
   - ANN (Artficial Neural Network) 
5. Model Selection & Performance Comparison  
6. Saving the Best Performing Model

---

## 🤖 Machine Learning Models Used
The following models were trained and evaluated:

| Model                     | Accuracy |
|---------------------------|----------|
| Random Forest Classifier  | 64%      |
| XGB Classifier            | 64.6%    |
| Artificial Neural Network | 62%      |

---

## 📈 Results Summary
The trained model successfully learns patterns from soil and environmental features and can recommend the most suitable crop type for given input conditions.  

