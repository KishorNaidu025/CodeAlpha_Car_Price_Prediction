# CodeAlpha Car Price Prediction

## Project Overview
This project focuses on predicting the selling price of used cars using machine learning techniques. It analyzes vehicle details such as manufacturing year, kilometres driven, fuel type, seller type, transmission, and ownership information to estimate the car's market price.

The project was completed as part of the CodeAlpha Data Science Internship.

## Objectives
- Analyze and understand the used-car dataset.
- Perform data cleaning and preprocessing.
- Explore relationships between car features and selling prices.
- Train machine learning regression models.
- Evaluate and compare model performance.
- Predict the selling price of a car using its features.

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## Machine Learning Models
The following regression algorithms were implemented:

1. Linear Regression
2. Random Forest Regressor

## Project Workflow
1. Import the required Python libraries.
2. Load the car dataset.
3. Perform data exploration and statistical analysis.
4. Clean the dataset and handle missing values.
5. Perform exploratory data analysis and visualization.
6. Separate input features and target variable.
7. Apply numerical and categorical data preprocessing.
8. Split the dataset into training and testing sets.
9. Train Linear Regression and Random Forest models.
10. Evaluate model performance using MAE, RMSE, and R² score.
11. Compare model performance and generate sample predictions.
12. Save the trained model using Joblib.

## Model Evaluation
The models are evaluated using the following metrics:

- **MAE (Mean Absolute Error):** Measures the average absolute difference between actual and predicted prices.
- **RMSE (Root Mean Squared Error):** Measures prediction error while giving greater weight to larger errors.
- **R² Score:** Measures how well the model explains variations in car selling prices.

The model comparison results are available in the project notebook.

## Project Files
- `CodeAlpha_Car_Price_Prediction.ipynb` – Complete Google Colab notebook containing data analysis, preprocessing, model training, and evaluation.
- `CodeAlpha_Car_Price_Prediction_Model.pkl` – Saved trained Random Forest model.

## How to Run
1. Download or clone this repository.
2. Open the `.ipynb` notebook in Google Colab.
3. Upload the car dataset.
4. Run the notebook cells in sequence.
5. Review the evaluation results and sample predictions.

## Internship
**Organization:** CodeAlpha  
**Domain:** Data Science  
**Project:** Car Price Prediction using Machine Learning

## Conclusion
This project demonstrates how machine learning regression algorithms can be used to estimate used-car selling prices based on vehicle features. It provided practical experience in data preprocessing, exploratory data analysis, model development, evaluation, and prediction.

