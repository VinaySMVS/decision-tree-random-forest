# 🌳 Heart Disease Prediction using Decision Tree and Random Forest

This project uses **Decision Tree** and **Random Forest Classifiers** to predict the presence of heart disease based on clinical features. It is part of my AI & ML Internship Task 5.

---

## 🎯 Objective

- Build a Decision Tree model and visualize it
- Control overfitting by limiting tree depth
- Train a Random Forest and compare performance
- Interpret important features
- Evaluate models using cross-validation

---

## 📁 Dataset

- Source: [Heart Disease Dataset - Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- Filename: `heart.csv`
- Target: `target` (0 = No Disease, 1 = Disease)

---

## 📈 Steps Performed

1. Data preprocessing and train-test split
2. Feature scaling with `StandardScaler`
3. Trained full and pruned **Decision Tree**
4. Visualized tree structure using `plot_tree()`
5. Trained a **Random Forest Classifier**
6. Compared accuracy and model performance
7. Plotted **feature importance**
8. Applied **5-fold Cross-Validation**

---

## 🧪 Results

| Model              | Accuracy Range |
|-------------------|----------------|
| Decision Tree      | 85% – 88%      |
| Pruned Tree (max_depth=4) | ~89%     |
| Random Forest      | 90% – 93%      |

---

## 🔍 Evaluation Metrics Used

- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)
- Feature Importance
- Cross-Validation (cv=5)

---

## 🧠 Key Concepts Covered

- Entropy & Information Gain
- Overfitting and Tree Depth Control
- Bagging in Random Forest
- Feature Importance Analysis
- Ensemble Learning

---

## 🛠️ Tools Used

- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 📂 Files in this Repository

| File                                | Description                         |
|-------------------------------------|-------------------------------------|
| `heart_disease_tree_forest.zip`     |  Input dataset from Kaggle          |
| `heart_disease_tree_forest.ipynb`   | Main notebook with all models       |
| `README.md`                         | Explanation of the project          |

---

## 🙋 Author

This project is submitted by **VinaySMVS**  
📌 Internship Task 5 – Tree-based Models

