# Heart Disease Prediction

This project uses logistic regression to predict whether a person has heart disease based on medical attributes. It showcases fundamental machine learning skills applied to healthcare data classification.

## 📂 Project Structure

- `Heart_Disease_Prediction.ipynb`: The main notebook with all steps — data loading, processing, model training, and evaluation.
- `heart_cleveland_upload.csv`: Dataset containing patient records and clinical features.

## 🚀 Features

- **Data Collection & Loading:** Reads the Cleveland heart disease dataset.
- **Data Exploration:** Checks data dimensions, class balance, and statistical summaries.
- **Preprocessing:** Handles feature-target separation, train-test splitting, and data normalization.
- **Model Building:** Implements logistic regression using scikit-learn.
- **Model Evaluation:** Calculates accuracy, checks predictions on training and test data.

## 📊 Dataset

The dataset includes clinical parameters for each patient. Key features:

- Age  
- Sex  
- Chest Pain Type  
- Resting Blood Pressure  
- Cholesterol  
- Fasting Blood Sugar  
- ECG Results  
- Max Heart Rate Achieved  
- Exercise Induced Angina  
- ST Depression  
- Slope of ST  
- Major Vessels Colored  
- Thalassemia  
- **Condition**:  
  - `0`: Healthy Heart  
  - `1`: Defective Heart

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/PraveenMudalgeri/ML-Projects.git
   cd "ML-Projects/Heart Disease Prediction"
   ```

2. Install required libraries:
   - pandas  
   - numpy  
   - scikit-learn  
   - jupyter

3. Launch the notebook:
   ```bash
   jupyter notebook Heart_Disease_Prediction.ipynb
   ```

## 🧠 Machine Learning Approach

- Logistic Regression used as the classifier.
- Dataset split into 80% training and 20% testing.
- Accuracy measured on both train and test sets.
- Straightforward and interpretable classification pipeline.

## 📈 Results

- Achieved strong classification accuracy using logistic regression.
- Predictions were evaluated and validated against test set outcomes.

## ✨ Author

- **Praveen Mudalgeri** (AIML Engineering Student)

---

> This project is a great foundation for future enhancements like trying other models (Random Forest, SVM) or adding hyperparameter tuning.
