# Used-car-price-prediction

## Project Overview 
This project aims to predict the prices of used cars based on various car specifications such as model, year, engine, fuel type, etc. The dataset used for this project was collected from the Cardheko website.

## Project Objective 
To develop a machine learning model that accurately predicts the price of used cars based on their features.

## Libraries Used
* pandas: For data manipulation and analysis.
* numpy: For numerical operations. 
* seaborn: For data visualization.
* matplotlib: For plotting graphs and visualizing data.

## Machine Learning Algorithms Used
The following regression algorithms were implemented to predict the car prices:
1. RandomForestRegressor
2. LinearRegression
3. KNeighborsRegressor
4. DecisionTreeRegressor
  
Each model’s accuracy was measured and compared to select the most accurate prediction model. 

## Data Source 
The dataset was gathered from the **Cardheko** website, containing various attributes of cars such as:
* Car Model
* Year of Manufacture
* Mileage
* Engine Capacity
* Fuel Type 
* Transmission Type
* Number of Owners
* Car Price (target variable)

## How to Run the Project
  1. Clone the repository to your local machine.
  2. Install the required libraries:

      ``` pip install pandas numpy seaborn matplotlib scikit-learn```
     
  4. Run the Jupyter notebook or Python script to see data analysis and model predictions.

## Project Structure
* data/: Contains the dataset used for training and testing.
* notebooks/: Contains the Jupyter notebooks with the code. 
* models/: Saved models after training.
* README.md: Project description.

## Future Improvements 
* Add more features to improve model accuracy. 
* Implement hyperparameter tuning for the models.
* Add a web-based interface for easy predictions.
