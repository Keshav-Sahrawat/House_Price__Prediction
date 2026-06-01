# House Price Prediction using Linear Regression

## Project Overview

This project implements a Machine Learning model to predict house prices using various housing attributes. The project follows a complete ML workflow including data analysis, preprocessing, model training, prediction, and evaluation.

---

## Objective

The objective of this project is to build a Linear Regression model capable of predicting house prices based on multiple features such as income, house age, number of rooms, number of bedrooms, and area population.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Dataset Information

The dataset contains housing information including:

- Average Area Income
- Average Area House Age
- Average Area Number of Rooms
- Average Area Number of Bedrooms
- Area Population
- Address
- House Price

Target Variable:

- Price

Dataset Source:
USA Housing Dataset

---

## Project Workflow

### 1. Data Collection

- Imported housing dataset.
- Loaded data using Pandas.

### 2. Data Exploration

- Checked dataset structure.
- Generated statistical summaries.
- Checked missing values.

### 3. Exploratory Data Analysis

- Price Distribution Analysis
- Feature Correlation Analysis
- Scatter Plot Analysis
- Heatmap Visualization

### 4. Feature Selection

Selected relevant numerical features:

- Avg. Area Income
- Avg. Area House Age
- Avg. Area Number of Rooms
- Avg. Area Number of Bedrooms
- Area Population

Removed:

- Address

Target Variable:

- Price

### 5. Model Building

Used:

- Linear Regression

### 6. Model Training

- Split dataset into training and testing sets.
- Trained model using training data.

### 7. Prediction

- Generated predictions on test data.

### 8. Model Evaluation

Evaluation Metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

---

## Results

The Linear Regression model achieved a strong prediction performance with a high R² score, demonstrating a strong relationship between housing features and house prices.

---

## Project Structure

```
House_Price_Prediction/
│
├── House_Price_Prediction.ipynb
│
├── data/
│   └── USA_Housing.csv
│
├── screenshots/
│
└── README.md
```

---

## Visualizations Included

- Price Distribution
- Correlation Heatmap
- Income vs Price Analysis
- Actual vs Predicted Price Plot

---

## Learning Outcomes

Through this project, the following concepts were practiced:

- Data Analysis
- Data Visualization
- Feature Selection
- Train-Test Split
- Linear Regression
- Model Evaluation
- Machine Learning Workflow

---

## Conclusion

This project demonstrates how Linear Regression can be used to predict house prices using multiple housing-related features. The model successfully captures relationships between input variables and housing prices, making it a practical introduction to supervised machine learning.

---

## Author

Keshav

B.Tech Artificial Intelligence Student

Learning Machine Learning, Data Analytics, Backend Development, and AI through hands-on projects.