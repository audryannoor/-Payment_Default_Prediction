# Payment_Default_Prediction
Dataset : [JANATA BANK Payment Default Prediction](https://www.kaggle.com/datasets/reverie5/av-janata-hack-payment-default-prediction)

**Background**
---
Bank Janata Taiwan in 2005 had a problem that has 22.12% default rate. That 22.12% default rate is too high than the fair value of the default rate that should be.This will made Bank Janata more lose revenue if it is not handled properly. We have to decrease the default rate to under 15% and increase potential revenue up to 5% by:
- Predict whether customers will default or not next month using predictive modelling
- Annalyze the factor that affect the increase in default rate

**Business Metric**
---
Default Rate = Total Customer of Default/ Total All Customer * 100%

**Exploratory Data Analysis**
---
1. Most credit card customer are women
2. Customers with university and high school educational backgrounds become customers with potential high to default
3. Customers with an age range under 25 years become customers with potential high to default
4. The last payment (September) has a high potential to determine the customer will default

**Data Pre-processing**
---
1.Handling Duplicate Value and Missing Value
2.Feature Encoding
3.Data Transformation
4.Outlier Handling
5.Feature Selection
6.Imbalance Target Handling

**Modelling**
---
1. Evaluation target is Precision (True Positive / (True Positive + False Positive))
2. 6 Model are tested and comapare each model result to get best precision value
3. Random forest has the highest precision value compared to other models where the precision value obtained is 66%

**Business Insights & Recommendation**
---
