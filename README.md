## Rock vs Mine Prediction

A **machine learning classification project** that identifies whether sonar signals are from a _rock_ or a _mine_.

### Overview

- **Goal:** Distinguish between rocks and underwater mines using _sonar signal data_.
- **Technology:** Python, Pandas, NumPy, scikit-learn
- **ML Algorithm:** Logistic Regression

### Dataset

- **Source:** Standard Sonar dataset (`sonar dataset.csv`)
- **Features:** 60 numerical values representing sonar signal strengths
- **Labels:** `R` (rock) or `M` (mine)

### Installation

- Clone the repository:
```
git clone https://github.com/your-username/rock-vs-mine-prediction.git
```
```
cd rock-vs-mine-prediction
```

- Install dependencies:
```
pip install -r requirements.txt
```


### How It Works

- Loads and pre-processes the dataset.
- Splits data into training and test sets.
- Trains a logistic regression model.
- Evaluates the model’s accuracy.

### Usage

- Ensure `sonar dataset.csv` is in the project directory.
- For Jupyter notebook:
- Open `Rock_vs_Mine_Prediction.ipynb`
- Run all cells in order.
- For Python script (if available):
- Run: 
  ```
  python rock_vs_mine_prediction.py
  ```

### Results

- The notebook or script prints test accuracy.
Model Accuracy: 76%


### Requirements

- Python 3.x
- Pandas
- NumPy
- scikit-learn

Install using:
`pip install pandas numpy scikit-learn`


### Project Structure

<pre> 
  rock-vs-mine-prediction/ 
  ├── Rock_vs_Mine_Prediction.ipynb 
  ├── sonar dataset.csv 
  ├── requirements.txt 
  └── README.md 
   </pre>


### Contributing

- Fork the repository and open pull requests to contribute.

### License

- MIT License

---
