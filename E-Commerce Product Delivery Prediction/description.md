# E-Commerce Product Delivery Prediction

![](https://globalskylogistics.com/wp-content/uploads/2018/04/THE-CHANGING-NATURE-OF-E-COMMERCE-DELIVERY.jpg)

## Project Overview:
This project aims to predict whether products from an international e-commerce company will arrive at customers on time. It also analyzes various factors influencing product delivery and examines customer behavior. The focus is primarily on electronic products.

## Data Dictionary:
The dataset used for model development contains 10,999 observations across 12 variables, including:

| Variable             | Description                                             |
|----------------------|---------------------------------------------------------|
| ID                   | Customer ID number                                     |
| Warehouse_block      | The warehouse block of the company (A, B, C, D, E)     |
| Mode_of_Shipment     | Shipment mode (Ship, Flight, Road)                     |
| Customer_care_calls  | Number of inquiries made by customers regarding shipment|
| Customer_rating      | Customer rating (1 - Lowest, 5 - Highest)              |
| Cost_of_the_Product  | Cost of the product in US Dollars                      |
| Prior_purchases      | Number of prior purchases made by the customer         |
| Product_importance   | Importance level of the product (low, medium, high)    |
| Gender               | Customer gender (Male, Female)                         |
| Discount_offered     | Discount provided on specific products                 |
| Weight_in_gms        | Weight of the product in grams                          |
| Reached.on.Time_Y.N  | Target variable (1 - Product did not reach on time, 0 - Product arrived on time) |

## Conclusion:
The project focused on predicting the timeliness of product deliveries while exploring factors that influence delivery and customer behavior. Exploratory data analysis indicated that product weight and cost significantly affect delivery outcomes. Products weighing between 2500 and 3500 grams and costing less than $250 had a higher chance of being delivered on time. Most shipments originated from Warehouse F, which is likely close to a seaport.

Customer behavior significantly impacts delivery predictions. A higher volume of customer inquiries correlated with delays, while customers with more prior purchases exhibited a greater likelihood of receiving their orders on time, suggesting brand loyalty. Additionally, products with discounts of 0-10% were more often delivered late, whereas those with discounts above 10% had better on-time delivery rates.

In terms of machine learning models, the decision tree classifier achieved the highest accuracy at 69%, outperforming other models. The random forest classifier and logistic regression followed with accuracies of 68% and 67%, respectively, while the K-Nearest Neighbors model had the lowest accuracy at 65%.