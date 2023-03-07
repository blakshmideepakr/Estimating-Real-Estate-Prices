<h1 align="center"> Estimating Real Estate Prices </h1>
<div align="center"> Bangalore Housing Dataset </div> 


<div style="text-align: justify">
This data science project walks through the step-by-step process of how to build a real estate price prediction website. The dataset used for the project is Bengaluru House Price Prediction Data from Kaggle. 

Generally, we come across real estate websites that sell and estimate the property's price in many parts of the country. The model we are implementing here is inspired by the same concept, the prediction of real estate properties based on the property's area, bedrooms, bathrooms, and location.

The following steps have been carried out for building the website for the real estate prices prediction.

1. The first step of the project is to preprocess the data for machine learning model development. In this project, the data preprocessing covers various data science methods: data wrangling, exploratory data analysis, data visualization, feature engineering, dimensionality reduction, gridsearchcv for hyperparameter tuning, k-fold cross-validation, etc.
2. In the second step a machine learning model is built using scikit-learn and linear regression algorithm.
3. I then wrote a python flask server that uses the saved model to serve HTTP requests.
4. Finally, I built a website using HTML, CSS, and JavaScript that allows users to enter the property's area, bedrooms, bathrooms, and location, which then calls a python flask server to retrieve the predicted price. 
</div>
