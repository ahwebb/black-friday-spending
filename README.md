# Black Friday Spending

## Introduction
This project will model customers' Black Friday spending based on a variety of purchasing and demographic features. Regression will be applied to determine the monetary amount a customer will spend on future Black Fridays, and classification will be applied to determine whether or not a customer is married based on their purchase history.

## The Data
Data set for this project can be found here: https://www.kaggle.com/sdolezel/black-friday. It contains a sample of purchases made by consumers in a retail store during Black Friday. The data set is hypothetical, and engineered with modeling in mind. We have several features related to the customer, including: Gender, Age, Occupation, Marital Status, what type of city they live in, and how long they have been living in that city. We also have some features related to the product they purchased: category the item falls under, and two subcategories to further classify the item. Finally, we have the total amount (in USD) spent on the consumer's Black Friday purchase.


## Modeling Approach
As mentioned earlier in the introduction, the Black Friday data will be modeled with 2 questions in mind: 1) How much will a customer spend on Black Friday?, 2) Is the customer married, based on their purchase history? Regression and classification will be used to answer these two proposed questions.

### Regression
* KNN
* Random Forest
* Ridge
* LASSO

### Classification
* KNN
* Random Forest
* Gradient Boosted Random Forest

## Conclusions
After feature engineering and parameter optimization, it was difficult to determine the amount a Black Friday consumer would spend based on the data set we have here. Modeling produced R2 values that were not reliable, and more data would be required to accurately predict customer purchasing habits. Classification fared substantially better, though marital status (perhaps predictably!) was based generally on demographic features and less on purchasing features.

## Future Goals
* Weight data or create more data points to project a reasonable estimate for purchasing amount
