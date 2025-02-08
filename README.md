# California Housing Price Prediction

This project trains a machine learning model to predict **home prices in California** based on various features such as location, population, and income levels. The main objective is to predict **median house values** using multiple features from the dataset.

## **Objective**

The goal of this project is to predict **median house values** (in US Dollars) for various regions in California. The model uses 9 feature variables and 1 target variable.

### **Feature Variables**
- **longitude**: A measure of how far west a house is (higher = farther west).
- **latitude**: A measure of how far north a house is (higher = farther north).
- **housingMedianAge**: Median age of a house within a block (lower values indicate newer buildings).
- **totalRooms**: Total number of rooms in a block.
- **totalBedrooms**: Total number of bedrooms in a block.
- **population**: Total number of people in a block.
- **households**: Total number of households in a block.
- **medianIncome**: Median income for households in a block (measured in tens of thousands of USD).
- **oceanProximity**: The proximity of the house to the ocean.

### **Target Variable**
- **medianHouseValue**: Median house value in a block (measured in USD).

## **Technologies Used**
This project uses the following libraries:
- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations and handling arrays.
- **matplotlib**: For visualizing data.
- **seaborn**: For enhanced data visualizations.
- **scikit-learn**: For building machine learning models and making predictions.

## **Dependencies**
Install the necessary dependencies before running the project:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
