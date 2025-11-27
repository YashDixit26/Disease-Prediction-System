# 🩺 AI-Powered Disease Prediction & Medical Recommendation System

An end-to-end **Machine Learning–based Intelligent Healthcare Assistant** that predicts diseases from user-reported symptoms and provides complete medical guidance — including disease description, precautions, medications, diet plans, and workout suggestions.

This project bridges the gap between raw medical datasets and real-world usability by combining **Machine Learning, Data Science, and Information Retrieval** into one cohesive system.

---

## 🚀 Why This Project Is Different

Unlike basic disease prediction projects that only return a label, this system is designed to behave like a **digital health assistant**:

✅ Understands imperfect symptom input (even with spelling mistakes)  
✅ Uses symptom severity weighting instead of plain 0/1 values  
✅ Handles class imbalance using SMOTE  
✅ Compares and tunes multiple ML models (Random Forest & XGBoost)  
✅ Returns a full medical guidance package — not just a prediction  

It doesn’t just predict a disease — **it explains it and guides the user forward.**

---

## 🧠 System Architecture

This system is built using a layered and modular design:

### 1. Data & Modeling Layer
Responsible for:
- Cleaning and analyzing the symptom dataset  
- Handling class imbalance using SMOTE  
- Training and tuning machine learning models  
- Saving the best model for future use  

Models used:
- 🌲 Random Forest  
- ⚡ XGBoost  

### 2. Knowledge & Recommendation Layer
A medical information engine that maps diseases to:
- Description  
- Precautions  
- Medications  
- Recommended Diets  
- Workout Plans  

This data is loaded from structured datasets and returned alongside predictions.

### 3. Intelligent User Input Layer
Makes the system user-friendly:
- Supports natural symptom input  
- Corrects spelling using fuzzy matching  
- Builds symptom vectors using severity weighting  
- Ensures robust predictions from noisy real-world inputs  

---

## ⚙️ How It Works (Pipeline Overview)

1️⃣ User enters **5–10 symptoms** (written naturally)  
2️⃣ System corrects spelling using fuzzy matching  
3️⃣ Symptoms are converted into a severity-weighted feature vector  
4️⃣ Trained ML model predicts the most likely disease  
5️⃣ System fetches disease-related information from multiple datasets  
6️⃣ User sees:

- Predicted Disease  
- Description  
- Precautions  
- Medications  
- Diet  
- Workout Suggestions  

All this happens in a smooth, single flow.

---

## 🔍 Features

📊 Extensive Exploratory Data Analysis with visualizations  
🎯 Multi-class disease classification  
⚖️ SMOTE-based class balancing  
🧪 Hyperparameter tuning using RandomizedSearchCV  
🤖 Spell correction of symptoms using FuzzyWuzzy  
📚 Integrated medical knowledge base  
💾 Model serialization using Pickle  

---

## 📂 Project Structure

