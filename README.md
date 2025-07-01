# Diabetes Prediction Project

This repository contains a Jupyter Notebook for predicting diabetes using machine learning algorithms on the provided healthcare dataset.

## How to use

1. **Clone this repository** or download the files.
2. **Upload `Healthcare-Diabetes.csv` and `diabetes_prediction.ipynb` to your notebook environment** (Colab or Jupyter).
3. **Run each cell in order** in the notebook.
4. **The notebook will train and evaluate several models**. You can use the saved model (`diabetes_rf_pipeline.pkl`) for future predictions.

### Requirements

- Python 3.x
- pandas, numpy, scikit-learn, seaborn, matplotlib, joblib

You can install requirements with:
```python
!pip install pandas numpy scikit-learn seaborn matplotlib joblib
```

### Making Predictions

To predict new cases, edit the `new_data` DataFrame in the last cell of the notebook with your own values.

---

**If you have any issues, please open an issue or discussion in this repository.**
