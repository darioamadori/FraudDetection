# About the Dataset

## Description
This synthetic dataset, titled "Fraudulent E-Commerce Transactions," simulates transaction data from an e-commerce platform, specifically designed for the purpose of fraud detection. It features a range of transaction-related attributes, along with additional engineered attributes to aid the development and testing of fraud detection algorithms.

## Dataset Overview
- **Number of Transactions in Version 1:** 1,472,952
- **Number of Transactions in Version 2:** 23,634
- **Features:** 16
- **Fraudulent Transactions:** Approximately 5%

## Feature Details
- **Transaction ID:** A unique identifier for each transaction.
- **Customer ID:** A unique identifier for each customer.
- **Transaction Amount:** The total amount exchanged in the transaction.
- **Transaction Date:** The date and time of the transaction.
- **Payment Method:** The method used to complete the transaction (e.g., credit card, PayPal).
- **Product Category:** The category of the product involved in the transaction.
- **Quantity:** The number of products involved in the transaction.
- **Customer Age:** The age of the customer.
- **Customer Location:** The geographical location of the customer.
- **Device Used:** The type of device used for the transaction (e.g., mobile, desktop).
- **IP Address:** The IP address from which the transaction was made.
- **Shipping Address:** Where the product was shipped.
- **Billing Address:** Associated with the payment method.
- **Is Fraudulent:** A binary indicator (1 for fraudulent, 0 for legitimate).
- **Account Age Days:** The age of the customer's account at the time of the transaction.
- **Transaction Hour:** The hour of the day the transaction occurred.

## Purpose
The dataset is aimed at developing and testing Machine Learning models for fraud detection in e-commerce transactions, as well as for exploratory data analysis, feature engineering, and benchmarking fraud detection algorithms.

## Generation Method
The dataset is completely synthetic, generated using Python's Faker library and custom logic to emulate realistic transaction patterns and fraudulent scenarios. It is designed purely for educational and research purposes and does not involve real individuals or transactions.

## Usage
This dataset is available for data analysis, Machine Learning projects, or as a benchmark for fraud detection algorithms. If you utilize this dataset in your research or projects, please ensure to provide proper attribution.
