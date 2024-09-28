# **Breast Cancer Prediction Using Machine Learning**

## **Overview**
This project aims to predict breast cancer diagnoses (Malignant or Benign) using machine learning models based on tumor characteristics. Data preprocessing, model training, and AutoML techniques were employed to achieve high accuracy and optimize performance.

## **Dataset**
The dataset contains tumor features such as radius, texture, and perimeter, with the target variable being the diagnosis (Malignant or Benign). The dataset can be accessed here:https://www.kaggle.com/uciml/breast-cancer-wisconsin-data

## **Workflow**
1. **Data Preprocessing**:
   - Cleaned data by dropping missing values and encoding diagnosis labels (M → 1, B → 0).
   - Standardized features using `StandardScaler`.

2. **Model Training**:
   Trained multiple models, including:
   - Ridge Classifier
   - AdaBoost Classifier
   - Extra Trees Classifier
   - Decision Tree Classifier
   - Random Forest Classifier

3. **AutoML with PyCaret**:
   - Compared models using PyCaret's `setup()` and `compare_models()` functions.
   - Tuned the best-performing model (Random Forest) to maximize accuracy.
   - Visualized results with confusion matrices and feature importance plots.

4. **Model Evaluation**:
   The Random Forest model achieved the best performance with high precision, recall, and F1-score. The model was saved for future predictions.

## **Technologies Used**
- Python, Pandas, NumPy, Scikit-learn, PyCaret
- Visualization: Matplotlib, Seaborn

## **Results**
The project successfully predicted breast cancer diagnoses with high accuracy, showcasing the power of machine learning in healthcare applications.

---

For more information, contact me at:
- **Email:** himanisharma15435029@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/himani-s1001/
