# Bike Sharing Assignment
> BoomBikes, a US-based bike-sharing provider, faces significant revenue challenges due to the ongoing COVID-19 pandemic. To prepare for a post-pandemic market recovery, BoomBikes has embarked on a strategic initiative to understand the factors influencing the demand for shared bikes in the American market. The primary objective of this project is to develop a predictive model that will help BoomBikes anticipate and meet customer demand effectively.

The project involves the following key steps:

- Data Collection and Preprocessing: Gather and clean a dataset (`day.csv`) containing information on daily bike demand and various influencing factors, including meteorological and demographic variables.

- Exploratory Data Analysis (EDA): Explore the dataset to identify patterns, correlations, and insights regarding how the independent variables relate to bike demand.

- Feature Selection: Determine which factors are most significant in predicting bike demand using feature selection techniques.

- Linear Regression: Regression model will be considered for this numerical prediction task.

- Model Training and Evaluation: Train the model on data and evaluate its performance using appropriate metrics Root Mean Squared Error (RMSE).

This project aims to equip BoomBikes with a data-driven understanding of the demand dynamics in the American market. By building an accurate predictive model, BoomBikes can make informed decisions regarding bike availability, marketing, and other strategies to enhance their revenue and position themselves as a leader in the bike-sharing industry when the COVID-19 situation improves.


## Table of Contents
* Introduction
In the wake of the ongoing COVID-19 pandemic, BoomBikes, a prominent bike-sharing service provider in the United States, has faced significant revenue challenges. As the company looks toward a post-pandemic recovery, it seeks to understand the intricacies of the bike-sharing market and the factors that influence demand. This project, "Predicting Bike Demand for BoomBikes", is a data-driven initiative aimed at building a predictive model that will enable BoomBikes to anticipate and respond to the evolving demands of customers effectively. By analyzing a wealth of data, this project endeavors to unlock valuable insights and guide BoomBikes in crafting a successful and adaptive business strategy for the future.

* Technologies Used
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Selection
- Model Selection
- Data Splitting
- Model Training
- Model Evaluation

* Conclusion
The final results of the model's performance indicate a strong predictive capability:

Train R^2: 0.838
Train Adjusted R^2: 0.835
Test R^2: 0.809
Test Adjusted R^2: 0.799

An R-squared value of 0.809-0.838 suggests that the model explains a substantial portion of the variance in the target variable, which is the demand for shared bikes. The adjusted R-squared values are also very close to the R-squared values, indicating that the model is not overfitted. This is a positive sign, as it suggests that the model is performing well both on the training data and the test data.

Furthermore, the similar performance on the training and test datasets indicates that the model is likely to generalize effectively to new, unseen datasets. In other words, it can make accurate predictions for bike demand in various scenarios beyond the data it was trained on.

These results are promising and imply that the model can be a valuable tool for BoomBikes in understanding and predicting demand dynamics, which can guide business decisions and strategies effectively.

* Acknowledgements
Credit to Data Sources (`day.csv`)
Project mentor - `Akashdeep Makkar`


## Technologies Used
- matplotlib
- pandas
- seaborn
- sklearn
- statsmodel

## Contact
Created by [@vikaaas-99] - feel free to contact me!
