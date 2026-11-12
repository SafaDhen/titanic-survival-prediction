# Titanic Survival Prediction

Predicts which passengers survived the Titanic disaster using a Random Forest classifier and hand-made features.

Kaggle challenge: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic). Solo project.



## Approach

1. Explore the data and handle missing values (age, cabin, embarked)
2. Feature engineering: 
3. Train a `RandomForestClassifier` 
4. Evaluate with and predict the test set


## Tech stack

Python, pandas, NumPy, scikit-learn, Matplotlib, Jupyter Notebook

## Getting started

```bash
git clone https://github.com/SafaDhen/titanic-survival-prediction.git
cd titanic-survival-prediction
pip install -r requirements.txt
jupyter notebook
```

Download `train.csv` and `test.csv` from the [Kaggle page](https://www.kaggle.com/c/titanic/data) into a `data/` folder. The data is not included.

## What I learned

- The training set is tiny (891 rows) . This teaches you that you don't always need "Big Data" to learn the fundamentals.
  It also highlights the limitations of small data: models can be unstable, and small changes in feature selection can cause large swings in accuracy,
  reinforcing the need for cross-validation. 

