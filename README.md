# Payment Default Prediction
Dataset : [JANATA BANK Payment Default Prediction](https://www.kaggle.com/datasets/reverie5/av-janata-hack-payment-default-prediction)

**Background**
---
Bank Janata Taiwan in 2005 had a problem that has 22.12% default rate. That 22.12% default rate is too high than the fair value of the default rate that should be.This will made Bank Janata more lose revenue if it is not handled properly. We have goal to decrease the default rate to under 15% and increase potential revenue up to 5% by:
- Predict whether customers will default or not next month using predictive modelling
- Analyze the factor that affect the increase in default rate

**Business Metric**
---
Default Rate = Total Customer of Default / Total All Customer * 100%

**Exploratory Data Analysis**
---
1. Most credit card customer are women
2. Customers with university and high school educational backgrounds become customers with potential high to default
3. Customers with an age range under 25 years become customers with potential high to default
4. The last payment (September) has a high potential to determine the customer will default

**Data Pre-processing**
---
1. Handling Duplicate Value and Missing Value
2. Feature Encoding
3. Data Transformation
4. Outlier Handling
5. Feature Selection
6. Imbalance Data Handling

**Modelling**
---
1. Evaluation target is Precision (True Positive / (True Positive + False Positive))
2. 6 Model are tested and compared each model result to get best precision value
3. Random forest has the highest precision value compared to other models where the precision value obtained is 66%

**Business Insights & Recommendation**
---
We create a business flow to make it easier to explain implement the model we created to achieve the goal.After implemented the model, we know who customer will potentially default next month and who non default. If model predict customer will default, we have recomendation that bank janata can do. We hope that the recommendations we provide can be achieved where the customer who is predicted to default will be no default.


![Business Flow](https://user-images.githubusercontent.com/68262798/184369070-eca30e7a-ab21-4e56-97e4-0b3e25b5d021.png)

Recomendation :
1. SMS & Phone Reminder
2. Payment Scheme with Installments
3. Credit restructuring
4. Billing for Customers who do not make payments

We assume that if the recommendations we provide are implemented then we can potentialy decrease the default rate to 14% , potentialy increase Bank Revenue by 9%, and potentialy decrease loss by 33%
![Decrease Default Rate](https://user-images.githubusercontent.com/68262798/184372392-150e7c87-fb50-46d3-a931-c166e134a196.png)

![Result](https://user-images.githubusercontent.com/68262798/184373660-1531b5d6-2a1b-4f95-930a-41cd63b0e9fd.png)
