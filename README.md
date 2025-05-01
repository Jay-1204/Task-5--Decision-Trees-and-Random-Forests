# Task-5--Decision-Trees-and-Random-Forests

# Heart Disease Classification using Decision Trees and Random Forests

## 📌 Objective
To train and evaluate tree-based models (Decision Tree and Random Forest) using a heart disease dataset. This project demonstrates classification, model visualization, overfitting analysis, feature importance, and cross-validation evaluation.

## 📁 Files Included
- `decision_tree_random_forest_heart.py` : Python script containing all steps.
- `heart_disease.csv` : The dataset used for training and testing.
- `README.md` : Project overview and instructions.

## ✅ What I Did
1. Trained a Decision Tree Classifier and visualized the decision tree.
2. Analyzed overfitting by varying tree depth.
3. Trained a Random Forest Classifier and compared it to the decision tree.
4. Interpreted feature importances using a bar plot.
5. Evaluated both models using cross-validation (5-fold).

## 🔧 Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## 📊 Results
- Random Forest generally performed better and avoided overfitting.
- Feature importances showed that `ca`, `thal`, and `cp` were influential in predicting heart disease.

## 🚀 How to Run
```bash
pip install pandas scikit-learn matplotlib seaborn
python decision_tree_random_forest_heart.py
```

## 📸 Screenshots
(Add any plots or terminal outputs here)

---
Created for AI & ML Internship - Task: Decision Trees and Random Forests
