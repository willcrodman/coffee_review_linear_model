# Modeling Coffee Reviewing with Linear Regression

### Will Rodman - Final Project for Math 6040 Linear Models

This project delves into data from [coffeereviews.com](www.coffeereviews.com) with the objective of developing a predictive linear regression model for coffee bean ratings. The primary goal is to explore the relationship between coffee bean features and their ratings, and determine how different levels of roasting affect these ratings.

### Project Overview:
- **Data Source:** The data was sourced from Kaggle, specifically [this dataset](https://www.kaggle.com/datasets/hanifalirsyad/coffee-scrap-coffeereview/versions/2/data?select=coffee_df.csv).

- **Key Questions:**
  - Which features of a coffee bean best determine its rating?
  - How do ratings vary with different levels of coffee bean roast?
  - How effectively can a linear model predict coffee bean ratings?

### Statistical Analysis:
- **Descriptive Analysis:** Initial exploration and visualization of numerical and categorical features.
- **Data Transformation:** Handling skewness and transforming features to fit normality.
- **Linear Regression:** Employing Ordinary Least Squares (OLS) method to fit models. Key metrics such as R-squared and F-statistic were used to assess model performance.
- **ANOVA:** Analysis of Variance to test the significance of the `roast` feature on coffee ratings.

### Model Development:
The models were developed iteratively, adjusting features and assessing improvements in R-squared and F-statistic values. The transformation of certain features like `100g_USD` was also explored.

### Conclusion:
The project successfully demonstrates the use of linear regression in understanding the impact of various features on coffee ratings. The final models provide a solid foundation for predicting ratings based on quantifiable coffee bean attributes.
