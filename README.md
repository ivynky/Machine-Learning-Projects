
# The Cosmic Mystery of Spaceship Titanic: A Data Science Investigation
Data source: (https://www.kaggle.com/competitions/spaceship-titanic)

##Overview:

In the year 2912, a routine interstellar voyage turned mysterious when the Spaceship Titanic encountered a spacetime anomaly, leaving the fate of its passengers uncertain. This project tackles a fictional yet structured data science challenge: predicting whether passengers were transported to an alternate dimension following the event.
Using a dataset recovered from the ship’s damaged computer system, we aim to apply machine learning techniques to understand patterns in the data and accurately classify passenger outcomes.

## Dataset Summary:

The dataset is divided into two parts:

train.csv: Contains personal records for approximately two-thirds (~8,700) of the passengers. This dataset includes:

  PassengerId: Unique identifier, where the first four digits denote group ID and the last two indicate group member.  
  HomePlanet: Origin planet.  
  CryoSleep: Whether the passenger chose suspended animation.  
  Cabin: Location onboard, structured as deck/number/side (Port or Starboard).  
  Destination: Target planet.  
  Age: Passenger's age.  
  VIP: Indicator of VIP status.  
  RoomService, FoodCourt, ShoppingMall, Spa, VRDeck: Charges for onboard amenities.  
  Name: Passenger’s full name.  
  Transported: Target variable; whether the passenger was transported to another dimension.

test.csv: Contains the remaining one-third (~4,300) of records, used for final prediction.)

## Objective:
The goal is to build a classification model that can predict the Transported status of each passenger in the test set based on the available features.

## Methodology:
1. Data Exploration
- Reviewed dataset structure and identified missing values.
- Analyzed feature distributions and correlations with the target variable.

2. Preprocessing and Feature Engineering
- Converted categorical variables to dummy variables.
- Standardized continuous variables for consistent scaling.
- Handled missing data using appropriate imputation techniques.

3. Model Development
- Split the training data into 80% training and 20% validation sets.

Evaluated three supervised learning models:
- Logistic Regression
- Decision Tree
- Random Forest

4. Model Evaluation
- Performance was assessed using accuracy as the primary metric.
- Logistic regression emerged as the best-performing model with an accuracy of 79% on the validation set.

5. Final Prediction
The logistic regression model was used to generate predictions for the test dataset..

## Key Takeaways:
- Simpler models like logistic regression can perform competitively on structured data with proper preprocessing.
- Effective handling of categorical variables and missing data was essential to achieving strong model performance.
- The project showcases end-to-end implementation of a classification problem, from data cleaning to model deployment

