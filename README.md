# -Payment_Default_Prediction
Dataset : [JANATA BANK Payment Default Prediction](https://www.kaggle.com/datasets/reverie5/av-janata-hack-payment-default-prediction)

**Background**
Bank Janata Taiwan in 2005 had a problem that has 22.12% default rate. That 22.12% default rate is too high than the fair value of the default rate that should be.This will made Bank Janata more lose revenue if it is not handled properly. We have to decrease the default rate to under 15% and increase potential revenue up to 5% by:
* Predict whether customers will default or not next month using predictive modelling
* Annalyze the factor that affect the increase in default rate

**Business Metric**
Default Rate = Total Customer of Default/ Total All Customer * 100%

**Objective**
Memprediksi user mana saja yang akan default, kemudian memberikan **Treatment** khusus pada user tersebut sehingga diharapkan agar tidak default pada bulan tersebut

**Exploratory Data Analysis**
1. Most credit card customer are women
2. Customers with university and high school educational backgrounds become customers with potential high to default
3. Customers with an age range under 25 years become customers with potential high to default
4. The last payment (September) has a high potential to determine the customer will default

**Data Pre-processing**
1. Tidak ditemukan data yang null
2. Tidak ditemukan data yang duplicate
3. Membuat Feature baru untuk memperkuat prediksi model yang akan dibuat (Age Group, Membership, Minimum Amount (1-5), Pending amount(1-5)
4. Melakukan feature encoding pada beberapa data kategorikal (Age_Group, Limit_Segment)

**Modeling**
1. Split data Train dan Test dengan ratio 70:30 (14900:6100)
2. Metric utama yang akan digunakan dalam mengevaluasi performa model adalah precision
3. Menerapkan beberapa algoritma seperti Decision Tree, kNN, Logistic Regression, Random Forest, XGboost, AdaBoostpada untuk membuat model yang kemudian akan dibandingkan performanya
4. Berdasarkan hasil perbandingan tiap model, Model AdaBoost dan Random Forest memiliki nilai precision yang tinggi dibandingkan model lain.

