# 🩺 Disease Prediction System Using Patient Data

An end-to-end **Machine Learning based Intelligent Healthcare System** that predicts diseases from user-entered symptoms and provides complete medical guidance including **description, precautions, medications, diet, and workout recommendations**.

This project combines data science, machine learning, and information retrieval to simulate a real-world smart healthcare assistant.

---

## ✅ 1. Project Objective

The aim of this project is to build an intelligent system that:

- Predicts diseases based on patient symptoms  
- Handles medical dataset class imbalance using SMOTE  
- Uses advanced machine learning models with hyperparameter tuning  
- Supports symptom spell correction  
- Provides full disease recommendations after prediction  

---

## ✅ 2. Key Features

🧠 **Disease Prediction Using ML**  
Predicts diseases from patient symptoms using optimized ML models.

📊 **Multiple Model Training & Comparison**  
Trains and evaluates:
- Random Forest  
- XGBoost  

⚖ **Class Imbalance Handling**  
Uses **SMOTE (Synthetic Minority Over-sampling Technique)** to balance disease categories.

🔎 **Smart Symptom Matching**
- Spell correction using **FuzzyWuzzy**  
- Can detect and correct wrongly typed symptoms.

📚 **Intelligent Recommendation System**
Provides after prediction:
- Disease description  
- Precautions  
- Recommended medications  
- Diet suggestions  
- Workout recommendations  

📈 **Advanced Data Visualization**
Includes:
- Disease distribution plots  
- Symptom correlation heatmap  
- Symptom frequency analysis  
- Disease–Symptom matrix visualization  

---

## ✅ 3. System Architecture


---

## ✅ 4. Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Core programming |
| Jupyter Notebook | Development environment |
| Pandas | Data preprocessing |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Advanced plots |
| Scikit-learn | ML algorithms |
| XGBoost | Boosted ensemble model |
| Imbalanced-learn | SMOTE for class balancing |
| FuzzyWuzzy | Spell correction |
| Pickle | Model saving/loading |

---

## ✅ 5. Dataset Information

This project uses multiple healthcare datasets:

### Main Training Dataset:
- Contains patient symptoms and disease labels (`prognosis`)
- Binary encoded symptom columns  

### Additional Recommendation Datasets:
- `Symptom-severity.csv` → Severity weight of symptoms  
- `precautions_df.csv` → Precautions for diseases  
- `workout_df.csv` → Workout plans  
- `description.csv` → Disease descriptions  
- `medications.csv` → Recommended medicines  
- `diets.csv` → Suggested diet plans  

---

## ✅ 6. Workflow Explanation

### Step 1: Data Preprocessing  
- Null values detection  
- Duplicate removal  
- Label encoding of disease names  
- Feature-target separation  

### Step 2: Exploratory Data Analysis  
- Disease class distribution visualization  
- Symptom frequency analysis  
- Correlation and co-occurrence heatmaps  
- Disease–Symptom matrix visualization  

### Step 3: Class Balancing  
SMOTE is applied to handle class imbalance and prevent biased predictions.

---

### Step 4: Model Training  
Two models are trained:
- Random Forest Classifier  
- XGBoost Classifier  

Evaluation metrics used:
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

---

### Step 5: Hyperparameter Tuning  
RandomizedSearchCV is used for both models to optimize performance.

Best hyperparameters are selected and models retrained.

---

### Step 6: Final Prediction System  
After tuning:
- Random Forest selected as primary model  
- Trained model saved using Pickle  

Users input 5–10 symptoms. The system:
1. Corrects spellings  
2. Applies severity weighting  
3. Predicts disease  
4. Displays medical guidance  

---

## ✅ 7. Installation & Setup

### 🔧 Prerequisites
- Python 3.8+  
- Jupyter Notebook  

### 📦 Install Required Libraries

Create a file named `requirements.txt`:



