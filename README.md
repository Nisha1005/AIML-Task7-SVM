# AIML-Task7-SVM
#  Support Vector Machine (SVM) Classification – Breast Cancer Dataset

This project demonstrates **Support Vector Machines (SVM)** for both linear and non-linear classification using the **Breast Cancer Wisconsin dataset**.

---

## 🎯 Objective

- Understand how SVMs work for binary classification.
- Train SVM models with different kernels.
- Visualize decision boundaries.
- Tune SVM hyperparameters like `C` and `gamma`.
- Evaluate model performance using cross-validation.

---

## 📁 Dataset

- **Source**: Scikit-learn built-in `load_breast_cancer()`
- **Target**: Binary classification (Malignant = 0, Benign = 1)
- **Features**: Various cancer cell measurements

---

## ⚙️ Tools & Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib / Seaborn
- Scikit-learn (SVM, scaling, evaluation, cross-validation)

---

## ✅ Steps Performed

### 1. Load & Prepare the Dataset
- Loaded the dataset using `load_breast_cancer()`
- Converted to a DataFrame and added the target
- Standardized features using `StandardScaler`

### 2. Train SVM Models
- Trained **Linear SVM** (`kernel='linear'`)
- Trained **RBF SVM** (`kernel='rbf'`) with default and tuned parameters

### 3. Visualize Decision Boundaries
- Selected 2 features for 2D visualization
- Plotted decision boundaries using `matplotlib`

### 4. Hyperparameter Tuning
- Adjusted `C` and `gamma` in the RBF model
- Compared model performance before and after tuning

### 5. Cross-Validation
- Evaluated model accuracy using `cross_val_score` with 5-fold CV

---
