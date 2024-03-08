Ames Housing Price Prediction
Welcome to the Ames Housing Price Prediction project! This competition provides an excellent opportunity for individuals with some experience in R or Python and machine learning basics to hone their skills in advanced regression techniques and creative feature engineering.

Description
Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. However, this competition's dataset from Ames, Iowa, demonstrates that many factors influence price negotiations beyond the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing almost every aspect of residential homes, this competition challenges participants to predict the final price of each home.

Practice Skills
Creative feature engineering
Advanced regression techniques like random forest and gradient boosting
Getting Started
To begin, you can take advantage of the provided starter notebook to jumpstart your exploration and modeling process.

Acknowledgments
The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It serves as an excellent alternative for data scientists seeking a modernized and expanded version of the often-cited Boston Housing dataset.


Evaluation
Goal
Your task is to predict the sales price for each house. For each ID in the test set, you must predict the value of the SalePrice variable.

Metric
Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. Taking logs ensures that errors in predicting expensive houses and cheap houses will equally affect the result