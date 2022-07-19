# Boston-Housing
# Overview of Efforts
In this project, I have applied basic machine learning concepts on data collected for housing prices in Boston, Massachusetts area to predict the selling price of a new home.I Have-
* Imported The Relevant Libraries
* Created a Pandas Dataframe,Explored The Dataset and added another value to store Target attribute in it
* Created a Heatmap to find correlation between different features and labels
* Normalized The Dataset
* Decided The Features to be used for prediction referring the Heatmap and trained the model
* Trained and Tested 3 Machine Learning Models-
  * Linear Regression
  * SVM Regressor
  * Random Forest Regressor
* Displayed The R2 Scores for all 3 Models
# Description
The Boston housing market is highly competitive, and you want to be the best real estate agent in the area. To compete with your peers, you decide to leverage a few basic machine learning concepts to assist you and a client with finding the best selling price for their home. Luckily, you've come across the Boston Housing dataset which contains aggregated data on various features for houses in Greater Boston communities, including the median value of homes for each of those areas. Your task is to build an optimal model based on a statistical analysis with the tools available. This model will then be used to estimate the best selling price for your clients' homes.
# Highlights
This project is designed to get acquainted to working with datasets in Python and applying basic machine learning techniques using NumPy and Scikit-Learn. Before being expected to use many of the available algorithms in the sklearn library, it will be helpful to first practice analyzing and interpreting the performance of your model.

Things I have learned by completing this project:

* How to use NumPy to investigate the latent features of a dataset.
* How to analyze various learning performance plots for variance and bias.
* How to determine the best-guess model for predictions from unseen data.
* How to evaluate a model's performance on unseen data using previous data.
# Deciding Features to be used for Training the Model
I created a Heatmap to find the correlation between different features and labels.Heatmap is a graphical representation of data using colors to visualize the value of the matrix.After seeing the correlation between MEDV and different features and taking into account Multicollinearity(Multicollinearity is a statistical concept where several independent variables in a model are correlated.Removing Multicollinearity is an important step during feature selection process),I arrived at the conclusion of using the following features for model testing and training-
1. NOX- nitric oxides concentration (parts per 10 million)
2. RM- average number of rooms per dwelling
3. DIS- weighted distances to five Boston employment centres
4. PTRATIO- pupil-teacher ratio by town
5. LSTAT- % lower status of the population

Target Variable-MEDV- Median value of owner-occupied homes in $1000's

# Conclusion
We have implemented 3 models for House Price Prediction-Linear Regression,SVM Regressor,Random Forest Regressor.Their R2 Scores are-

* Linear Regression-0.7417818906824027
* SVM Regressor-0.8518907744570283
* Random Forest Regressor-0.8733895298130578

We can see that Random Forest Regressor Model has the highest R2 score and thus provides the highest accuracy for Boston House Prediction for the given features.
