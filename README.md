# PRODIGY_ML_01

## House Price Prediction using Linear Regression

### Internship
Machine Learning Internship at Prodigy InfoTech

### Task Objective
Build a Linear Regression model to predict house prices based on:
- Square Footage (GrLivArea)
- Number of Bedrooms (BedroomAbvGr)
- Number of Bathrooms (FullBath)

### Dataset
House Prices: Advanced Regression Techniques Dataset from Kaggle

### Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

### Machine Learning Algorithm
Linear Regression

### Project Workflow
1. Loaded the dataset using Pandas.
2. Selected relevant features:
   - GrLivArea
   - BedroomAbvGr
   - FullBath
3. Split the dataset into training and testing sets.
4. Trained a Linear Regression model.
5. Predicted house prices on the test dataset.
6. Evaluated model performance using multiple metrics.
7. Visualized Actual vs Predicted House Prices.

### Results

| Metric | Value |
|----------|----------|
| Mean Absolute Error (MAE) | 35788.06 |
| R² Score | 0.6341 |
| Root Mean Squared Error (RMSE) | Add Your RMSE Value Here |

### Visualization
Actual vs Predicted House Prices Scatter Plot



### Learning Outcomes
Through this project, I learned:
- Data preprocessing using Pandas
- Feature selection for machine learning models
- Train-Test Split
- Linear Regression implementation
- Model evaluation using MAE, RMSE, and R² Score
- Data visualization using Matplotlib

### Repository Structure

PRODIGY_ML_01
│
├── data/
├── house_price_prediction.py
├── predictions.csv
├── README.md
└── house_price_prediction_graph.png

### Conclusion
The Linear Regression model was able to predict house prices with reasonable accuracy using only three features. This project helped in understanding the complete machine learning workflow from data preparation to model evaluation.
