# Time Series-Iyzico trading volume estimate
🚩Expected Transaction Volume Estimate from Member Businesses.
🛒It is expected that the total transaction volume estimate will be made on a merchant_id and daily basis for the last 3 months of 2020.
🛒Data from 2017 to 2021 of a total of 7 member businesses in 7 categories are included.
👉Variables:
transaction_date: Date of sales data
merchant_id: IDs of member businesses (Unique number for each member business)
Total_Transaction: Number of transactions
Category: Categories of member businesses
Total_Paid: Payment amount
🚀STEPS:🚀
1-EDA    2- FEATURE ENGINEERING(date features, lag/shifted features, rolling mean fetures, exponentially weighted mean features)
3-MODELLING(lightGBM, SMAPE)
