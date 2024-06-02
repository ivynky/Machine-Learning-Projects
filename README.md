
## The Cosmic Mystery of Spaceship Titanic: A Data Science Investigation
Data source: (https://www.kaggle.com/competitions/spaceship-titanic)

Contributors: Nkiru Onyemekwu, Preeti Agrawal, Evangeline Olalusi

# Introduction:

Welcome to the year 2912, where the enigmatic Spaceship Titanic's collision with a spacetime anomaly has led to a cosmic mystery. Our task is to predict whether passengers were transported to an alternate dimension during this cataclysmic event. In this summary, we'll explore the dataset provided, consisting of personal records recovered from the ship's damaged computer system.

# Dataset Description:

train.csv: Personal records for about two-thirds (~8700) of the passengers, used as training data.

PassengerId: Unique ID for each passenger.gggg indicates a group the passenger is travelling with and pp is their number within the group.
HomePlanet: The planet the passenger departed from.
CryoSleep: Indicates if the passenger elected to be in suspended animation.
Cabin: The cabin number where the passenger stayed.Takes the form deck/num/side, where side can be either P for Port or S for Starboard.
Destination: The planet the passenger was headed to.
Age: Age of the passenger.
VIP: Indicates if the passenger paid for VIP service.
RoomService, FoodCourt, ShoppingMall, Spa, VRDeck: Amount billed at luxury amenities.
Name: First and last names of the passenger.
Transported: Whether the passenger was transported to another dimension (Target).
test.csv: Personal records for the remaining one-third (~4300) of the passengers, used for prediction (unseen data)

# Objective:
Our goal is to predict whether each passenger in the test set was transported to another dimension during the collision. We'll utilize machine learning techniques to analyze the provided data and make predictions.

# Approach:
Data Exploration: We'll explore the dataset to understand its structure, distribution, and deal with missing values.
Feature Engineering: We'll engineer new features if needed and preprocess the data for modeling.
Model Selection: We'll select appropriate machine learning models and train them using the training data.
Model Evaluation: We'll evaluate the performance of the trained models using appropriate evaluation metrics.
Prediction: Finally, we'll make predictions for the passengers in the test set and submit our results.

#Statistical Modeling:
Step 1: Converted the categorical variables to dummy varaiables
Step 2: Standardized the continous variables to ensure they all have the same scale
Step 3: Conducted a training and testing on the training dataset using a ratio of 80:20
Step4: Explored 3 models; logistic regression, decision tree and random forest to identify the most optimal model to use for the prediction.

# Findings:
Achieved 79% accuracy rate with the logistic regression which was the highest compared to the other models.
The outcome of the logistic regression was used to predict the unseen data
