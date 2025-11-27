# 🩺 AI-Powered Disease Prediction & Medical Recommendation System

An end-to-end **Machine Learning–based Intelligent Healthcare Assistant** that predicts diseases from user-reported symptoms and provides complete medical guidance — including disease description, precautions, medications, diet plans, and workout suggestions.

This project bridges the gap between raw medical datasets and real-world usability by combining **Machine Learning, Data Science, and Information Retrieval** into one cohesive system.

---

## 🚀 Why This Project Is Different

Most disease prediction systems stop at simply outputting a disease name.  
This project goes several steps further — it behaves like a **real-world AI healthcare assistant**, not just a classification model.

What makes it truly stand out:

✅ **Understands imperfect human input**  
People don’t always know or remember exact medical terms. This system is built for real users, not just perfect datasets. It uses smart fuzzy matching to recognize and correct misspelled or incomplete symptom names — making health prediction more accessible, even for non-technical users.

✅ **Severity-aware intelligence**  
Instead of assuming every symptom has the same importance, the model intelligently assigns severity weights to each symptom. This allows more critical symptoms (like high fever or chest pain) to influence predictions more strongly than minor ones — resulting in more realistic and medically meaningful outcomes.

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

## ⚙️ How It Works 

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

### 📚 Libraries and Their Roles

| Library                     | Purpose in This Project |
|-----------------------------|---------------------------|
| **NumPy**                   | Used for numerical computations and handling symptom vectors and arrays. |
| **Pandas**                  | Used for loading, cleaning, manipulating, and analyzing datasets (CSV files). |
| **Scikit-learn**            | Core machine learning library used for preprocessing, model training, evaluation, and hyperparameter tuning. |
| **XGBoost**                 | Used for building and training the XGBoost classification model for disease prediction. |
| **Imbalanced-learn (SMOTE)** | Used to handle class imbalance by generating synthetic samples for minority disease classes. |
| **FuzzyWuzzy**              | Used to perform fuzzy string matching for correcting and matching user-entered symptom spellings. |
| **Matplotlib**              | Used for data visualization like bar charts, model performance plots, and statistical graphs. |
| **Seaborn**                 | Used for advanced visualizations such as heatmaps for symptom correlation and disease-symptom relationships. |


---

## ⚠️ Important Disclaimer

This system is intended for **educational and research purposes only**.

It is **NOT** a substitute for professional medical advice, diagnosis, or treatment.  
Always consult a qualified healthcare professional for medical concerns.

---

## 👨‍💻 Author

**Yash Dixit**  

