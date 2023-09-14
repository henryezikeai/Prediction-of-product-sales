# Prediction-of-product-sales

### Author 

- Henry Ezike

### Objective

To predict the product sales for a certain period. 

### Insights

### Image 1 - Correlation Heatmap

<img width="820" alt="Screen Shot 2023-09-11 at 8 34 31 AM" src="https://github.com/henryezikeai/Prediction-of-product-sales/assets/8410149/f2118286-8c87-4fd0-baed-46642ec5a211">

From the Heatmap above, we can deduce that there is positive relationship between Item MRP and Outlet sales. 

### Image 2 - Items Distribution

<img width="657" alt="Screen Shot 2023-09-11 at 8 38 12 AM" src="https://github.com/henryezikeai/Prediction-of-product-sales/assets/8410149/da036c4d-8832-43f2-960f-0bc002b949e4">

From the item distribution, we can see that Fruits and Vegetables have the highest count when it comes to products being sold at an outlet. 
And Seafood has the lowest count. 

# Model Evaluation

The R^2 score of 0.592 for our Random Forest Regressor indicates that the model explains 59.2% of the variance in the target variable. While this performance is moderate, it surpasses that of the Linear Regression model. Ideally, we aim for an R^2 score close to 1 on both training and test datasets, with a particular emphasis on the test data.


# Model Insights - Linear Regression

![Screen Shot 2023-09-13 at 6 15 53 PM](https://github.com/henryezikeai/Prediction-of-product-sales/assets/8410149/31365d25-7e7a-4631-a10b-5c7f87c2256d)

### Interpretation

From the coefficients barplot, we can deduce that Outlet_Identifier_OUT013, Outlet_Establishment_Year, outlet_type etc all contribute positively towards total sales. 

# Model Insigts - RandomForest

![Screen Shot 2023-09-13 at 6 27 21 PM](https://github.com/henryezikeai/Prediction-of-product-sales/assets/8410149/58dfc41c-54a3-4f88-9843-85f30d4ff7d6)

### Interpretation

From the feature importances barplot, we can deduce that Item_MRP, Item_Visibility, Outlet_Type, Item_Weight, Outlet_Establishment_Year etc are the most importannt feature for predicting total sales.



