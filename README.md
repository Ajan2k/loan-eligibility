# Loan Eligibility Prediction

This project predicts loan eligibility using a machine learning model trained on a public dataset. The workflow includes data collection, preprocessing, exploratory data analysis (EDA), model training, and evaluation.

## Project Structure

```
.
├── dmodel.ipynb         # Main Jupyter notebook with code and analysis
├── data/
│   └── Loan_Data.csv    # Loan dataset (copied from Kaggle)
```

## Features

- Data collection from Kaggle using `kagglehub`
- Data cleaning and preprocessing (missing values, outlier removal, encoding)
- Exploratory Data Analysis (EDA)
- Model training using Random Forest Classifier
- Model evaluation with accuracy, confusion matrix, and classification report
- Visualization of results

## Requirements

- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- kagglehub

Install dependencies with:

```sh
pip install pandas numpy matplotlib seaborn scikit-learn kagglehub
```

## Usage

1. Download the dataset from Kaggle using the notebook's built-in code.
2. Run all cells in `dmodel.ipynb` to preprocess data, train the model, and evaluate results.
3. Review the output metrics and plots for model performance.

## Data Source

- [Loan Eligibility Dataset on Kaggle](https://www.kaggle.com/datasets/himanshikawade04/loan-eligiblity)

## License

This project is for educational purposes. Refer to the dataset's license for data usage terms.
