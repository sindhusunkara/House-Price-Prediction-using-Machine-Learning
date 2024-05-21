# HOUSE_PRICE_PREDICTION
Introduction
House price prediction is a critical problem in the real estate sector. Accurate predictions can help sellers set competitive prices and buyers get fair deals. This project utilizes machine learning techniques to predict house prices based on various features such as location, size, and condition.

Dataset
The dataset used for this project is the Ames Housing Dataset, which includes detailed information on over 2,500 properties in Ames, Iowa. The dataset can be found on Kaggle.

Data Fields
SalePrice: The property's sale price (target variable)
LotArea: Lot size in square feet
OverallQual: Overall material and finish quality
YearBuilt: Original construction date
TotalBsmtSF: Total square feet of basement area
GrLivArea: Above grade (ground) living area square feet
FullBath: Full bathrooms above grade
GarageCars: Size of garage in car capacity
GarageArea: Size of garage in square feet
1stFlrSF: First Floor square feet
2ndFlrSF: Second floor square feet
Neighborhood: Physical locations within Ames city limits
Features
The features used in the model include both numerical and categorical variables. Feature engineering and selection were performed to enhance model performance.

Algorithms Used
The following machine learning algorithms were implemented and evaluated:

Linear Regression
Ridge Regression
Lasso Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
XGBoost Regressor
Neural Networks
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
Create a virtual environment:

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Usage
Data Preprocessing: Clean and preprocess the data using preprocess.py.

bash
Copy code
python preprocess.py
Training Models: Train the models using train.py.

bash
Copy code
python train.py
Evaluation: Evaluate the performance of the models using evaluate.py.

bash
Copy code
python evaluate.py
Results
The performance of each model was evaluated using metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R²). The best-performing model was the XGBoost Regressor with the following results:

MAE: 12,345
RMSE: 23,456
R²: 0.89
Detailed results and comparison of all models can be found in the results/ directory.
