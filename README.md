# Airbnb-data-Data-Dive

### Nashville Airbnb Data Analysis Project Overview

This project is a collaboration with InsideAirbnb.com, aimed at deriving valuable insights from their collected data on Nashville's Airbnb listings. The main objective is twofold: firstly, to visualize, summarize, or explore an interesting insight that could enhance the website's dashboard, and secondly, to develop predictive models that offer both numerical predictions and decision-making label predictions relevant to InsideAirbnb.com's users.

### Purpose of the Project

The project's primary goal is to utilize data science techniques to analyze and model Airbnb data for Nashville, offering actionable insights and predictive models that can aid InsideAirbnb.com. Specifically, the project focuses on:

Visualizing and Exploring Data: Identify and present intriguing insights from the Airbnb data that could add value to the InsideAirbnb.com dashboard, making it more informative and engaging for users.
Numerical Prediction Model: Create a regression analysis model to predict a continuous variable, such as price, based on various listing features. The model aims to identify the most significant features affecting the target variable, employing techniques like Lasso and Ridge Regression to enhance prediction accuracy and feature selection.
Label Prediction Model: Develop a classification model to predict a binary outcome, enhancing decision-making for users. This involves creating a target variable and selecting a suitable model (e.g., Logistic Regression) to predict categories such as 'Highly Rated' vs. 'Not Highly Rated' listings.
Summary of Findings and Methodology

### Numerical Prediction Model (Regression Analysis):
Purpose: To predict the price of Airbnb listings based on amenities and other relevant features.
Approach: Employed Lasso and Ridge Regression models to estimate the relationship between price and listing features. Lasso Regression, in particular, was highlighted for its feature selection capability.
Key Findings: The optimal alpha for Lasso indicated strong model performance, with a high R² score suggesting the model explains a significant portion of price variability. Ridge Regression demonstrated stable performance across various alpha values.

### Label Prediction Model (Classification Analysis):
Objective: To predict whether an Airbnb listing would be highly rated, based on features impacting guest satisfaction.
Models Used: Logistic Regression was selected for its efficiency in binary classification, considering its ability to provide a balanced performance across different metrics.
Model Performance: The Logistic Regression model achieved an accuracy score of 0.7648, with notable recall, precision, and ROC AUC scores, indicating its reliability in predicting highly rated listings.

### Conclusion

The project not only sheds light on the significant factors influencing Airbnb listing prices and ratings in Nashville but also demonstrates the application of data science in real-world scenarios. By utilizing regression and classification models, the analysis provides InsideAirbnb.com with tools to better understand and predict listing performance, ultimately enhancing the platform's value for hosts and guests alike. This initiative encourages a data-informed approach to improving listing quality and user experience on the platform.
