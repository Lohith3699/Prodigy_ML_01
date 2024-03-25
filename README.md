**House Price Prediction using Linear Regression**
-----------------------------------------------------------
**Overview**
-----------------------------------------------------------
This project aims to predict house prices based on square footage, number of bedrooms, and number of bathrooms using a linear regression model. The dataset used contains information about various houses including their square footage, number of bedrooms and bathrooms, and the corresponding sale prices.

-----------------------------------------------------------
**Dataset**
-----------------------------------------------------------
The dataset used for this project is stored in a CSV file named house_price.csv. It includes the following columns:

. Square Footage: The total square footage of the house.

. Bedrooms: The number of bedrooms in the house.

. Bathrooms: The number of bathrooms in the house.

. Price ($): The sale price of the house.

**Requirements**
-----------------------------------------------------------
To run the code in this project, you'll need the following dependencies:

. Python 3.x

. pandas

. scikit-learn

. matplotlib (for plotting)

You can install the required packages using pip:

**Usage**
-----------------------------------------------------------
Clone this repository or download the house_price.csv file.
Install the required dependencies as mentioned above.
Run the house_price_prediction.py script to train the linear regression model and make predictions.
Code Structure

. house_price.csv: CSV file containing the dataset.

. house_price_prediction.py: Python script for training the linear regression model and making predictions.

. README.md: This README file providing an overview of the project and instructions for usage.

**Results**
-----------------------------------------------------------
After running the house_price_prediction.py script, you will get the mean squared error (MSE) and R-squared (R2) score as evaluation metrics for the model. Additionally, a scatter plot will be generated showing the predicted versus actual prices of the houses.
