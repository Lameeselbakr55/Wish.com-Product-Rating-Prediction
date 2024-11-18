# Wish.com-Product-Rating-Prediction

## **Project Overview**

This project is centered on predicting the product ratings of Wish.com products based on the other features known for a product on website.

**Competition Link:** https://www.kaggle.com/competitions/cisc-873-dm-w24-a1

**The inputs:**  features of the products on website like price, retail_price ,urgency_text, various feature of merchant like rate and others.

**The output:** The predicted product rating, which is in categories from 1 to 5.

**The data mining function:** classification.

**Challenges**
* data cleaning from noise, null values and outliers
* find best method to fill null values
* many values in color and size_id with the same name but wit special characters or upper and lower differences
* hadling categorical features
* find new values in test_data not found in train data
* select best model to deploy
* many parameter to choose from them for models


**Impact**

The impact of accurately predicting the product rating is that it can help businesses understand their customer base and tailor their products to meet customer preferences. It can also help businesses identify the features that are most important to customers, which can inform product development and marketing strategies.


**Ideal solution**

My experiment explor data well to find noise, try more than on solution to fill null to get better accuracy, get rid of noisy features, remove some corroleted feature to avoid high cordinate, collect values with low count in one value in color and size_id and use grid search technique to find best parameter.
but in general, an ideal solution would be to develop a machine learning model that accurately predicts the product rating based on the available features, while also being able to handle missing or noisy data. The model should also be easily interpretable, so that businesses can understand the factors that are most important for predicting product ratings. Additionally, the model should be regularly updated with new data to ensure its accuracy over time.
