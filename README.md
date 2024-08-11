# Fake-News-Detection

## Overview

This project aims to build a machine learning model to detect fake news using the LIAR dataset. The project leverages various data science techniques and libraries, focusing on data manipulation, visualization, and machine learning within a Jupyter Notebook environment.

## Libraries Used

- Pandas: Used for data manipulation and analysis. Provides easy-to-use data structures and data analysis tools.
- NumPy: Used for numerical computations, providing support for large multi-dimensional arrays and matrices.
- Matplotlib: Used for creating static, interactive, and animated visualizations in Python.
- Scikit-learn (sklearn): A machine learning library in Python that provides simple and efficient tools for data mining and data analysis.
- XGBoost: An optimized distributed gradient boosting library designed to be highly efficient, flexible, and portable.

## Project Workflow

1. Data Loading: The LIAR dataset is loaded and explored to understand its structure and content.
2. Data Preprocessing: The data is cleaned and preprocessed to ensure that it is ready for model training. This includes handling missing values, text preprocessing (e.g., removing stopwords), and feature engineering.
3. Exploratory Data Analysis (EDA): Visualizations are created using Matplotlib to explore the data and identify any trends or patterns.
4. Model Training:
    - Different machine learning models are trained on the processed data, including KNN, SVM, Decision Trees, and XGBoost.
    - Hyperparameter tuning is performed to optimize model performance.
5. Model Evaluation:
    - The models are evaluated using various metrics such as accuracy, precision, recall, and F1-score.
    - The performance of different models is compared to identify the best model for fake news detection.
6. Reflection:
    - Reflect on the results obtained and whether the initial objectives were met.
    - Discuss the strengths and limitations of the chosen models and dataset, and suggest possible improvements for future work.

## Installation

To run the code in this project, you will need to have Python installed, along with the required libraries. You can install the required libraries using pip:

```
pip install pandas numpy matplotlib scikit-learn xgboost jupyter
```

Clone the repository:

```
git clone https://github.com/yourusername/fake-news-detection.git
cd fake-news-detection
cd report
```

Launch Jupyter Notebook:

```
jupyter notebook
```

Then open the fnd.ipynb notebook and run the cells to see the results.
