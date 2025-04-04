# House Price Prediction Using Machine Learning

This project aims to predict house prices based on key features such as area, number of bedrooms, bathrooms, stories, and furnishing status. Using a machine learning model, we build a regression pipeline to estimate the price of a house, providing valuable insights for real estate businesses, agents, and buyers.

## Project Overview

The goal of this project is to build a machine learning model to predict house prices using various features of a house. The project uses **Ridge Regression** inside a **Pipeline** for preprocessing and model training, allowing us to prevent overfitting and improve model generalization.

### Features
- **area**: Size of the property (in square feet)
- **bedrooms**: Number of bedrooms in the house
- **bathrooms**: Number of bathrooms in the house
- **stories**: Number of stories (floors)
- **furnishingstatus**: The furnishing status of the property (e.g., furnished, semi-furnished, unfurnished)

### Target Variable
- **price**: Selling price of the property

## Steps Involved

1. **Data Cleaning and Preprocessing**: 
   - Handle missing values
   - Encode categorical variables (e.g., furnishing status)
   - Scale numerical features (e.g., area, bedrooms, etc.)

2. **Model Building**:
   - Use a regression model (Ridge Regression) inside a machine learning pipeline.
   
3. **Model Evaluation**:
   - Evaluate model performance using R² score and other metrics like RMSE.

4. **Interpretation**:
   - Display coefficients and intercept of the regression model to understand feature impacts on house price prediction.

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- ipywidgets (for interactive widgets)

### How to Run

1. Clone the repository:
git clone https://github.com/yourusername/house-price-prediction.git
2. Install the dependencies:
3. Run the notebook:
# Contributing

Feel free to fork the repository, make improvements, and submit pull requests. If you have any suggestions or improvements, please open an issue.

## License

This project is licensed under the MIT License.
