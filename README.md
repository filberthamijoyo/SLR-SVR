# Simple Linear Regression and Support Vector Regression (SVR)

This project demonstrates the implementation of **Simple Linear Regression** and **Support Vector Regression (SVR)** using Python. The code includes data preprocessing, model training, prediction, and visualization for both regression and classification tasks.

## Features

### 1. **Simple Linear Regression**
- **Dataset Handling**: Imports training and test datasets from text files.
- **Model Training**: Uses `scikit-learn`'s `LinearRegression` to fit the model.
- **Manual Calculation**: Implements linear regression manually using matrix operations.
- **Prediction**: Predicts target values for both training and test sets.
- **Visualization**: Includes code for visualizing actual vs. predicted values (commented out for now).

### 2. **Support Vector Regression (SVR)**
- **Dataset Handling**: Imports the Iris dataset from an Excel file.
- **Custom Data Splitting**: Splits the dataset into training and test sets while maintaining class distribution and original order.
- **Feature Scaling**: Standardizes features for better SVM performance.
- **Model Training**: Implements SVM with:
  - **Linear Kernel**
  - **Slack Variables** (Soft Margin)
  - **Kernel Functions** (Polynomial, RBF, Sigmoidal)
- **Error Analysis**: Calculates training and testing errors for each class.
- **Support Vectors**: Identifies support vectors for each model.

## Code Structure
- **Linear Regression**: 
  - Importing libraries and datasets.
  - Model training and prediction.
  - Manual weight calculation using matrix operations.
  - Visualization (commented out).
  
- **Support Vector Regression**:
  - Data preprocessing and splitting.
  - SVM implementation with different kernels and slack variables.
  - Error analysis and support vector identification.

## Usage
1. Clone the repository.
2. Ensure the required datasets (`linear_regression_train.txt`, `linear_regression_test.txt`, `Classification iris(2).xlsx`) are in the correct directory.
3. Run the Python script to see the results.

## Dependencies
- Python 3.x
- Libraries: `numpy`, `pandas`, `scikit-learn`, `matplotlib`

## Results
- **Linear Regression**: Displays bias, weights, and predicted values for the test set.
- **SVM**: Provides training and testing errors, support vectors, and slack variables for each class and kernel type.

## Future Work
- Add more visualization options.
- Extend the project to include other regression and classification algorithms.

---

Feel free to contribute or suggest improvements!
