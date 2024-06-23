# Heart Disease Prediction using Logistic Regression

This repository contains a Jupyter notebook that demonstrates the use of logistic regression to predict heart disease based on various health metrics. The dataset used for this project is the "Heart_Data.csv" file.

## Dataset

The dataset used in this project is `Heart_Data.csv`. It contains multiple health-related attributes, and the target variable indicates the presence or absence of heart disease.

## Project Structure

- `Logistic Reg.ipynb`: The Jupyter notebook containing all the steps from data loading, preprocessing, model training, and evaluation.
- `Heart_Data.csv`: The dataset file used for training and testing the model.

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- matplotlib
- seaborn
- scikit-learn

## Steps

1. **Data Loading**: The dataset is loaded using pandas.
2. **Exploratory Data Analysis (EDA)**:
   - Displaying the first few rows of the dataset.
   - Checking the shape and summary statistics of the dataset.
   - Visualizing the target variable distribution.
3. **Data Preprocessing**:
   - Handling missing values.
   - Splitting the dataset into features (X) and target (y).
   - Splitting the data into training and testing sets.
4. **Model Training**:
   - Training a logistic regression model using scikit-learn.
5. **Model Evaluation**:
   - Predicting the test set results.
   - Calculating accuracy.
   - Generating and visualizing the confusion matrix.
   - Plotting the ROC curve.


## Results

The logistic regression model achieves an accuracy of approximately 86% on the test set. The ROC curve is plotted to visualize the performance of the model.

## Conclusion

This project demonstrates a basic approach to predict heart disease using logistic regression. Further improvements can be made by exploring more sophisticated models and techniques.
