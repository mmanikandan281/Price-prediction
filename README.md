# Price-prediction
This repository contains code and data for a simple Linear Regression model that predicts home prices based on various features. It covers data preprocessing, model training, evaluation, and prediction
for more information visit my google collab link:https://colab.research.google.com/drive/1LS8UN6ieGcM4DyO-_Q5iZZjzxUgK1Tep?usp=sharing

# House Price Prediction Using Linear Regression

This repository demonstrates a simple implementation of house price prediction using a linear regression model in Python. The project uses sample data for house sizes (in square feet) and their corresponding prices (in thousands of dollars) to train and test the model.

---

## Features

- *Linear Regression Model:* Uses Scikit-learn's LinearRegression class to predict house prices.
- *Sample Dataset:* Includes a small dataset of house sizes and prices for demonstration purposes.
- *Price Prediction:* Predicts the price of a house based on its size.

---

## Installation

1. Clone this repository:
   ``` 
   https://github.com/mmanikandan281/Price-prediction.git
   ```
3. Navigate to the project directory:
   bash
   cd house-price-prediction
   
4. Install the required Python libraries:
   bash
   pip install numpy scikit-learn
5. Access the Colab
   ```
   https://colab.research.google.com/drive/1LS8UN6ieGcM4DyO-_Q5iZZjzxUgK1Tep?usp=sharing
  

---

## Usage

1. Open the Python script (house_price_prediction.py) in your preferred editor.
2. Run the script:
   bash
   python house_price_prediction.py
   
3. The script will output the predicted price for a house with a size of 2000 square feet.

---

## Code Overview

The key steps in the code are:

1. Import necessary libraries:
   python
   import numpy as np
   from sklearn.linear_model import LinearRegression
   

2. Define the dataset:
   python
   X = np.array([...]).reshape(-1, 1)
   y = np.array([...])
   

3. Create and train the linear regression model:
   python
   model = LinearRegression()
   model.fit(X, y)
   

4. Predict house prices:
   python
   predicted_price = model.predict([[2000]])
   

5. Output the results:
   python
   print("Predicted price for a 2000 sq. ft. house:", predicted_price[0])
   

---

## Example Output

After running the script, you will see output similar to the following:


Predicted price for a 2000 sq. ft. house: 289.56


--
