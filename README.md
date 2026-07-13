
# Olympic Medal Prediction using Machine Learning

A Machine Learning project that predicts the number of Olympic medals won by each country using historical Olympic data. The project performs data preprocessing, exploratory data analysis (EDA), feature engineering, and builds a Linear Regression model to estimate medal counts.

---

##  Project Overview

This project uses historical Olympic team statistics to predict the total medals won by a country. The workflow includes:

- Data loading and cleaning
- Exploratory Data Analysis (EDA)
- Correlation analysis
- Feature engineering
- Linear Regression model training
- Medal prediction
- Model evaluation using Mean Absolute Error (MAE)

---

##  Dataset

The project uses the following dataset:

- `teams.csv`

Key features include:

- Country/Team
- Number of Athletes
- Previous Olympic Medals
- Average Age
- Current Medal Count (Target Variable)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

##  Exploratory Data Analysis

The notebook includes:

- Correlation matrix
- Scatter plots
- Medal distribution histogram
- Missing value detection
- Feature relationship analysis

---

##  Machine Learning Model

**Algorithm Used**

- Linear Regression

### Input Features

- Number of Athletes (`athletes`)
- Previous Medals (`prev_medals`)

### Target

- Medal Count (`medals`)

---

## Model Evaluation

Evaluation Metric:

- Mean Absolute Error (MAE)

The notebook also compares:

- Actual medals
- Predicted medals
- Prediction error

Negative predictions are converted to zero and predictions are rounded to produce realistic medal counts.

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Olympic-Medal-Prediction.git
```

2. Install dependencies

```bash
pip install pandas numpy seaborn scikit-learn jupyter
```

3. Launch Jupyter Notebook

```bash
jupyter notebook
```

4. Open

```
machine_learning_mp.ipynb
```

5. Run all cells.

---

## Requirements

```
pandas
numpy
seaborn
scikit-learn
jupyter
```

---

## Future Improvements

- Random Forest Regressor
- XGBoost Regressor
- Feature scaling
- Cross-validation
- Hyperparameter tuning
- Interactive visualizations
- Prediction dashboard using Streamlit

---

## Learning Outcomes

- Data preprocessing
- Exploratory Data Analysis
- Correlation analysis
- Feature engineering
- Linear Regression
- Model evaluation
- Machine Learning workflow using Scikit-learn

---
