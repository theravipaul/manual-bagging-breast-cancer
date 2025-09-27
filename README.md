#📈 Model Performance Comparison — Manual Bagging Ensemble vs Base Model on Breast Cancer Dataset
![image alt](https://github.com/theravipaul/manual-bagging-breast-cancer/blob/5187d0ba56a1797216cadb1d1ae3327a9ca9854c/Screenshot%202025-09-27%20232441.png)
# Breast Cancer Classification - Ensemble Learning with Decision Trees

This machine learning project focuses on classifying tumors as **malignant** or **benign** using the Breast Cancer dataset. The approach includes both a base decision tree model and a manually constructed ensemble using bagging.

---

## 📋 Sections Covered in the Notebook

1. **Import Libraries**  
2. **Load and Explore the Dataset**  
3. **Data Cleaning & Preprocessing**  
4. **Visualize Important Features**  
5. **Train-Test Split**  
6. **Helper Functions**  
7. **Manual Bagging with Decision Trees**  
8. **Evaluate Ensemble Predictions**  
9. **Base Model (Single Tree) for Comparison**  
10. **Compare Sample Predictions**  
11. **Classification Report** *(new)*  
12. **Conclusion & Insights** *(new)*

---

## 📈 Results

| Model        | Accuracy | Notes |
|--------------|----------|-----------------------------|
| Base Model   | 84.8%    | Single Decision Tree        |
| Ensemble     | 85.8%    | Majority vote of 3 models   |

---

## 🚀 How to Run

1. Clone the repo  
2. Install required packages  
   ```bash
   pip install -r requirements.txt
