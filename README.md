# Breast-Cancer-Prediction-Using-Machine-Learning-Techniques

# Breast Cancer Prediction Using Machine Learning Techniques

This project implements and compares multiple machine learning algorithms for predicting breast cancer diagnoses using the UCI Wisconsin Breast Cancer dataset. The models were trained, tested, and evaluated to determine their effectiveness in medical diagnosis support.

## 🧠 Objective

To develop a predictive model that can accurately classify breast tumors as benign or malignant using historical data and machine learning methods.

## 📂 Dataset

- **Source:** UCI Machine Learning Repository
- **Name:** Wisconsin Breast Cancer Dataset
- **Features:** 30 numeric attributes (mean, standard error, worst)
- **Instances:** 569
- **Classes:** Malignant (M), Benign (B)

## 🔍 Methodology

1. **Preprocessing:**
   - Removed irrelevant fields (e.g., ID)
   - Label encoded categorical outcomes
   - Normalized features
   - Handled missing values (if any)
   - Data split: 80% training, 20% testing

2. **Models Used:**
   - Logistic Regression
   - Support Vector Machine (SVM)
   - Random Forest
   - Naive Bayes

3. **Evaluation Metrics:**
   - Accuracy
   - Precision
   - Recall
   - F1-Score

## 🧪 Results

| Model              | Accuracy | Precision | Recall | F1-Score |
|-------------------|----------|-----------|--------|----------|
| Logistic Regression | 94.73%   | 95.65%    | 93.33% | 94.48%   |
| SVM               | 94.73%   | 93.10%    | 96.67% | 94.85%   |
| Random Forest     | 96.49%   | 96.67%    | 96.67% | 96.67%   |
| Naive Bayes       | 92.98%   | 91.30%    | 93.33% | 92.30%   |

✅ **Best Performing Model:** Random Forest (Accuracy: 96.49%)

## ⚙️ Tools & Libraries

- Python
- Jupyter Notebook
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/breast-cancer-prediction.git
   cd breast-cancer-prediction
