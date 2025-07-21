# 📱 Mobile Price Range Prediction using Machine Learning

This project aims to classify mobile phones into 4 different price categories (ranging from 0 to 3) using various features like battery power, RAM, screen size, camera resolution, etc., with the help of supervised machine learning models.

---

## 📂 Table of Contents
- [About the Project](#about-the-project)
- [Dataset](#dataset)
- [Tech Stack](#tech-stack)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Building](#model-building)
- [Model Evaluation](#model-evaluation)
- [Model Explainability](#model-explainability)
- [Final Model](#final-model)
- [Conclusion](#conclusion)
- [Results](#results)
- [Project Demo](#ProjectDemo)
- [Contact](#contact)

---

## 📌 About the Project

The objective is to **predict the price range** of mobile phones using key specifications as input features. The classification is divided into 4 categories:

- 0: Low Cost
- 1: Medium Cost
- 2: High Cost
- 3: Very High Cost

This project demonstrates the end-to-end pipeline of solving a classification problem using real-world-like data.

---

## 📊 Dataset

- **Source**: Provided as part of the project (synthetic dataset).
- **Size**: 2000 rows × 21 columns
- **Target Variable**: `price_range`

---

## 🧰 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib, Seaborn
- Scikit-learn
- SHAP (for explainability)
- Google Colab

---

## 🔍 Exploratory Data Analysis

- Checked for null values and duplicates
- Visualized distributions of features like `battery_power`, `ram`, `int_memory`, etc.
- Used heatmaps and pairplots to understand feature relationships
- Created various charts to show feature distribution and their impact on `price_range`

---

## 🤖 Model Building

Models implemented:
- ✅ Logistic Regression
- ✅ Decision Tree
- ✅ Random Forest

---

## ✅ Model Evaluation

| Model                | Accuracy | Precision | Recall | F1-score | CV Score |
|---------------------|----------|-----------|--------|----------|----------|
| Logistic Regression | 0.93     | 0.93      | 0.93   | 0.93     | 0.9235   |
| Decision Tree       | 0.85     | 0.84      | 0.84   | 0.84     | 0.8415   |
| Random Forest       | 0.87     | 0.87      | 0.87   | 0.87     | 0.8675   |

**Evaluation Metrics Used:**
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Cross-Validation Score

---

## 🧠 Model Explainability

- Used **SHAP** to interpret the final model
- Visualized feature importance and individual prediction contributions

---

## 🏁 Final Model

**Selected Model:** Logistic Regression  
**Reason:** Achieved the highest accuracy (0.93), stable cross-validation score (0.9235), and interpretable results.  
**Top Features Influencing Price Range:**
- RAM
- Battery Power
- Internal Memory
- Mobile Weight

---

## 📌 Conclusion

This project provided hands-on experience with:
- EDA
- Supervised ML models for classification
- Model evaluation and hyperparameter tuning
- Explainability using SHAP

🎯 The final model can help businesses in:
- Strategic pricing decisions
- Product categorization
- Consumer targeting

---

## 📸 Results Snapshot

- ✅ Logistic Regression Accuracy: **93%**
- 📈 SHAP Visuals: Included for interpretability
- 📊 15+ Data Visualizations created

---

## 🔗 Project Demo

[👉 Click here to view full notebook](https://colab.research.google.com/drive/15eHuG4EcueT7vg_-Agc4UA_2jNP0Zhmr?usp=sharing)

---

## 📬 Contact

**Abhinav Kumar**  
_B.Tech CSE (Data Science)_  
[LinkedIn](https://www.linkedin.com/in/abhinav-kumar-b0b0ba253/) | [Email](abhinav8934g@gmail.com)

---

## ⭐️ Don't forget to star this repo if you found it helpful!


