# SpendDNA – Spotify Wrapped for Your Money 💰

SpendDNA is a personal finance analytics project that transforms raw transaction data into meaningful insights about spending habits. The project analyzes transaction records, identifies spending patterns, detects unusual transactions, and generates a personalized financial profile.

## 📌 Project Overview

SpendDNA processes a synthetic transaction dataset of a Bengaluru-based software engineer and converts messy banking data into structured, easy-to-understand financial insights.

The project focuses on understanding **where, when, and how money is spent**.

## 🚀 Key Features

* **Transaction Parser** – Cleans and standardizes dates, amounts, transaction types, and other fields.
* **Vendor Extractor** – Converts messy transaction descriptions into clean vendor names.
* **Category Tagger** – Groups transactions into categories such as Food, Shopping, Transport, Subscriptions, Investments, and more.
* **Spending Overview** – Calculates total spending, category-wise spending, and top vendors.
* **Monthly Trend Analysis** – Tracks spending patterns across different months.
* **Time-of-Day Analysis** – Identifies when most spending occurs during the day.
* **Anomaly Detection** – Uses category-wise z-scores to identify unusually large transactions.
* **Spending Archetypes** – Identifies spending behaviours such as Foodie, Shopaholic, Investor, Cab Commuter, and other profiles.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Google Colab
* GitHub
* CSV Dataset

## 📂 Project Structure

```text
SpendDNA/
│
├── SpendDNA_Week2.ipynb
├── rahul_transactions.csv
└── README.md
```

## 📊 Dataset

The project uses the provided `rahul_transactions.csv` dataset containing transaction records with information such as:

* Date
* Time
* Description
* Transaction Type
* Amount
* Balance
* Payment Mode
* Reference

The dataset contains intentionally messy transaction formats, which are cleaned and standardized during the analysis.

## 🎯 Objective

The main objective of SpendDNA is to demonstrate how basic data cleaning, transformation, aggregation, and analytical techniques can be used to turn raw financial transactions into useful personal spending insights.

## 📈 Outcome

The final analysis produces a personalized **“SpendDNA” profile** showing spending patterns, monthly trends, frequently used categories and vendors, unusual transactions, and behavioural spending archetypes.

## 👩‍💻 Project

**Week 2 Minor Project – The Unlox Academy**

Built using Python and data analysis techniques in Google Colab.
