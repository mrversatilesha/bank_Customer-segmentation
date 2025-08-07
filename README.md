🏦 Bank Customer Segmentation

📊 Overview
This project focuses on segmenting bank customers using machine learning techniques to better understand customer behavior, preferences, and demographics. The goal is to help financial institutions target specific customer groups for personalized marketing, product recommendations, and strategic decision-making.

Using a dataset of over 1 million+ transactions from 800K+ customers of an Indian bank, the project performs:
Exploratory Data Analysis (EDA),
Customer profiling,
Clustering using KMeans,
Data ingestion from Azure Blob Storage


📁 Dataset
The dataset includes:

Customer demographics: age (DOB), gender, and location

Transaction data: amount, date, type, and account balance


📂 Source: bank_transactions_part1.csv
🔒 Note: Sensitive information has been anonymized.


⚙️ Functionalities
🔍 1. Data Connection & Ingestion
Connects to Azure Blob Storage

Loads raw transactional data securely

📈 2. Exploratory Data Analysis
Distribution of customer age, gender, and balance

Transaction trends across time and geography

Identification of high-value and frequent users

🤖 3. Customer Segmentation
Feature engineering (age, transaction frequency, average balance)

Normalization and clustering using KMeans

Visual segmentation with plots for cluster interpretation

📊 4. Cluster Insights
Each cluster represents a customer type (e.g., high-net-worth, frequent low-value users)

Helps understand behavioral patterns in segments


🧰 Technologies Used
Python 🐍

Pandas & NumPy

Matplotlib & Seaborn

Scikit-learn (KMeans)

Azure SDK (Blob Storage)
