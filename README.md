# Wine Quality Prediction using Machine Learning

This project explores the application of multiple machine learning models to predict the quality of red wines based on various physicochemical properties. The goal is to support quality control in wine production using data-driven techniques.

---

## 📊 Objective

To build classification models that can accurately predict wine quality ratings from chemical features such as alcohol content, pH, citric acid, etc.

---

## 📁 Dataset

- **Source:** [Wine Quality Dataset – UCI / Kaggle](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)
- **Type:** CSV
- **Samples:** 1,599
- **Features:** 11 numeric chemical properties
- **Target:** `quality` (integer score ranging from 0–10)

---

## 🛠️ Tools & Libraries

- Python
- pandas, numpy
- seaborn, matplotlib
- scikit-learn (Logistic Regression, kNN, Random Forest, Boosted Trees)
- ROC AUC, Confusion Matrix, F1 Score

---

## 🧪 Workflow

1. Load and inspect the dataset
2. Perform exploratory data analysis (EDA)
3. Preprocess and scale data
4. Split data into training and testing sets
5. Train and evaluate multiple classification models
6. Compare performance using accuracy and F1 score

---

## 🧠 Models Applied

| Model              | Evaluation Metric |
|-------------------|-------------------|
| Logistic Regression | F1 Score: 0.88    |
| k-Nearest Neighbors | F1 Score: 0.88    |
| Random Forest       | F1 Score: 0.90    |
| Boosted Trees       | **F1 Score: 0.92** ✅ |

---

## ✅ Conclusion

- **Boosted Trees** achieved the highest performance with an **F1 Score of 0.92**.
- Alcohol content, volatile acidity, and sulphates were highly correlated with wine quality.
- The model demonstrates how machine learning can help automate and enhance quality control processes in the wine industry.

---

## 📎 Author

**Jaymin Patel**  
[GitHub Portfolio](https://jayminmech7.github.io)
