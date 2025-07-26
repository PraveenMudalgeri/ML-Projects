# Wine Quality Prediction

This project aims to predict the quality of wine using various physicochemical features and machine learning algorithms. By analyzing the provided dataset, multiple models are trained and evaluated to determine the best approach for accurate wine quality classification.

## 📂 Project Structure

- `Wine_Quality_Prediction.ipynb`: Jupyter notebook containing the entire data analysis, preprocessing, model building, evaluation, and results.
- `dataset.csv`: The cleaned dataset containing wine samples and their physicochemical properties.

## 🚀 Features

- Exploratory Data Analysis (EDA): Visualizing and understanding key patterns in the wine dataset.
- Data Preprocessing: Handling missing values, feature engineering, and data normalization.
- Model Training: Implementation of various algorithms (e.g., Logistic Regression, Random Forest, SVM).
- Evaluation Metrics: Accuracy, confusion matrix, classification report, and other diagnostics.
- Visualization: Graphs and plots to support findings and illustrate model performance.

## 📊 Dataset

The dataset contains several physicochemical attributes for red/white wines (like acidity, sulphates, alcohol, etc.) and the quality score (target variable) assigned by wine experts.

Common columns include:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (target)

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/PraveenMudalgeri/ML-Projects.git
   cd ML-Projects/Wine\ Quality\ Prediction
   ```

2. Install requirements (if provided), or make sure you have essential libraries:
   - pandas
   - numpy
   - matplotlib
   - seaborn
   - scikit-learn
   - jupyter

3. Open and run the notebook:
   ```bash
   jupyter notebook Wine_Quality_Prediction.ipynb
   ```

## 🧠 Machine Learning Approach

- Tested multiple ML algorithms for classification.
- Compared performance using evaluation metrics.
- Included hyperparameter tuning (if applicable).

## 📈 Results

- Detailed performance comparison is available in the notebook.
- Visualization of confusion matrices and prediction results.
