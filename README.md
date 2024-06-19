# House Price Predictor

![License](https://img.shields.io/badge/license-MIT-blue.svg)

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Evaluation](#evaluation)
- [Results](#results)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview
House Price Predictor is a machine learning project aimed at predicting house prices based on various features such as house size, number of bedrooms, number of bathrooms, and location. This project utilizes data preprocessing, feature engineering, and a Random Forest Regressor model to achieve accurate predictions.

## Dataset
The dataset used in this project contains information about houses in the USA, including:
- State
- City
- House Size
- Number of Bedrooms
- Number of Bathrooms
- Price

## Features
- Data cleaning and preprocessing to handle missing values and outliers.
- Feature encoding for categorical data.
- Data normalization and standardization.
- Model training using Random Forest Regressor.
- Hyperparameter tuning using GridSearchCV.
- Evaluation metrics: Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared.

## Installation
To run this project locally, please follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/House Price Regressor.git

2. Navigate to the project directory:
   ```bash
   cd House Price Predictor
   ```

3. Create a virtual environment and activate it:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
   ```

4. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
To use this project, follow these steps:

1. Ensure you have the dataset in the appropriate format.
2. Run the data preprocessing script:
   ```bash
   python preprocess_data.py
   ```
3. Train the model:
   ```bash
   python train_model.py
   ```
4. Evaluate the model:
   ```bash
   python evaluate_model.py
   ```

## Model
The model used in this project is a Random Forest Regressor, which is an ensemble learning method that combines multiple decision trees to improve prediction accuracy and control over-fitting.

## Evaluation
The model is evaluated using the following metrics:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R-squared (R²)**

## Results
| Metric         | Value           |
|----------------|-----------------|
| Mean Absolute Error (MAE) | 97819.64      |
| Mean Squared Error (MSE)  | 341560714398.64 |
| Root Mean Squared Error (RMSE) | 584431.95      |
| R-squared (R²)   | 0.9567          |

## Future Work
- Experiment with other machine learning models such as Support Vector Regression (SVR) and Neural Networks.
- Incorporate more features to improve model accuracy.
- Deploy the model as a web application for real-time predictions.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request or open an Issue for any bugs, feature requests, or improvements.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact
For any questions or feedback, please contact:

Pranshu Chauhan  
[Email](mailto:pranshu26092003@example.com)  
[LinkedIn](https://www.linkedin.com/in/pranshu-chauhan-72921b231)  
[GitHub](https://github.com/Pranshu-Chauhan)

