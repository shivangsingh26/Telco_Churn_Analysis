# Telco Customer Churn Analysis and Prediction

## Table of Contents
1. [Project Overview](#project-overview)
2. [Files in the Project](#files-in-the-project)
3. [Directory Structure](#directory-structure)
4. [Installation and Setup](#installation-and-setup)
5. [Usage](#usage)
6. [Key Features](#key-features)
7. [Data](#data)
8. [Model Performance](#model-performance)
9. [Future Improvements](#future-improvements)
10. [License](#license)
11. [Contact](#contact)

## Project Overview

This project focuses on analyzing and predicting `customer churn` for a telecommunications company. It includes `exploratory data analysis (EDA)`, `model building`, and a `web application` for making predictions.

## Files in the Project

1. `Churn_Analysis_EDA.ipynb`: Jupyter notebook containing exploratory data analysis.
2. `Churn_Analysis_Model_Building.ipynb`: Jupyter notebook for building and evaluating machine learning models.
3. `app.py`: Flask application for deploying the model as a web service.
4. `requirements.txt`: List of Python dependencies for the project.

## Directory Structure

- `data/`: Contains input data files.
- `exports/`: Stores output files (CSV files and model files) generated during the analysis.

## Installation and Setup

To run this project, you'll need Python 3.x and the required libraries. You can install the dependencies using the following command:

```
pip install -r requirements.txt
```

This will install the following libraries:

- `numpy`
- `pandas`
- `seaborn`
- `matplotlib`
- `scikit-learn`
- `imbalanced-learn`
- `flask`

## Usage

1. Exploratory Data Analysis:
   - Open and run `Churn_Analysis_EDA.ipynb` in a Jupyter environment.
   - This notebook processes the data, performs `univariate` and `bivariate analysis`, and exports the processed data to the `exports/` directory.

2. Model Building:
   - Open and run `Churn_Analysis_Model_Building.ipynb` in a Jupyter environment.
   - This notebook builds various models including `Decision Tree` and `Random Forest classifiers`, applies `SMOTEENN` for handling imbalanced data, and saves the best model to the `exports/` directory.

3. Web Application:
   
   - Run `app.py` to start the Flask server:

   
     ```
     python app.py
     ```
   - Access the web interface through your browser to input customer data and get churn predictions.

## Usage

1. **Exploratory Data Analysis:**
   - Open and run `Churn_Analysis_EDA.ipynb` in a Jupyter environment.
   - This notebook processes the data, performs univariate and bivariate analysis, and exports the processed data to the `exports/` directory.

2. **Model Building:**
   - Open and run `Churn_Analysis_Model_Building.ipynb` in a Jupyter environment.
   - This notebook builds various models including Decision Tree and Random Forest classifiers, applies SMOTEENN for handling imbalanced data, and saves the best model to the `exports/` directory.

3. **Web Application:**
   - Run `app.py` to start the Flask server:
     ```
     python app.py
     ```
   - Access the web interface through your browser to input customer data and get churn predictions.

## Key Features

- Comprehensive EDA with visualizations
- Machine learning models for churn prediction
- Handling of imbalanced dataset using SMOTEENN
- Web application for real-time predictions

## Data

The project uses the Telco Customer Churn dataset. Ensure you have the following files in your `data` directory:

- `Telco-Customer-Churn.csv`
- `first_telc.csv`

## Model Performance

The final model uses a Random Forest Classifier with SMOTEENN, achieving high accuracy and balanced performance across classes. The model file is saved in the `exports/` directory.

## Future Improvements

- Implement more advanced models (e.g., XGBoost, Neural Networks)
- Enhancing the web application with more features and better UI
- Incorporate more recent data for improved predictions

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any inquiries or issues, please contact the project maintainers at [ssnfs26@gmail.com].