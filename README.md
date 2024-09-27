# Ecommerce Data Analysis

This project analyzes customer data including personal information, purchase history, and financial details. The analysis focuses on identifying trends such as popular email providers, customers with expired credit cards, and purchase price statistics.

## Project Overview

The primary objectives of this analysis include:
- Extracting popular email providers from customer data.
- Identifying customers whose credit cards expired in 2020.
- Analyzing purchase prices and identifying high-value purchases.

## Dataset

The dataset contains the following fields:
- `Address`: Customer address.
- `Lot`: Additional address information.
- `Browser Info`: Information about the browser used for the transaction.
- `Company`: Company of employment.
- `CC Number`: Credit card number.
- `CC Exp Date`: Credit card expiry date.
- `CC Security Code`: Credit card security code.
- `CC Provider`: Provider of the credit card (e.g., Visa, MasterCard).
- `Email`: Customer email address.
- `Job`: Job title of the customer.
- `IP Address`: IP address of the transaction.
- `Language`: Language preference.
- `Purchase Price`: Price of the item purchased.

## Key Analyses

### 1. Top 5 Most Popular Email Providers
- Extracted the domain from each customer email address and identified the most common email providers.
  
### 2. Expired Credit Cards in 2020
- Counted the number of customers whose credit cards expired in the year 2020 using string manipulation techniques.

### 3. Purchase Price Distribution
- Analyzed the purchase prices to identify any high-value transactions and calculated average purchase prices.

## Functions

- `fun()`: Counts the number of credit cards that expired in 2020 by iterating over the dataset.


