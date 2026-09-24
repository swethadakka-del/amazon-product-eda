# amazon-product-eda
Exploratory Data Analysis of Amazon products using Python, Pandas, Matplotlib and Seaborn.
# Amazon Product Exploratory Data Analysis

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on an Amazon products dataset using Python.

The analysis focuses on understanding product prices, discounts, ratings, rating counts, and product categories through statistical analysis and data visualization.

## 🎯 Objectives

- Understand the structure of the Amazon products dataset
- Clean and preprocess numerical columns
- Analyze product price distributions
- Study discount percentages
- Analyze product ratings
- Identify category-wise patterns
- Detect potential outliers
- Study relationships between numerical variables
- Visualize correlations between important features

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub

## 📊 Exploratory Data Analysis

The project includes:

### Univariate Analysis

- Histograms
- Boxplots
- KDE plots
- Bar charts
- Count plots
- Pie charts

### Bivariate Analysis

- Scatter plots
- Category-wise analysis
- Price vs rating analysis
- Discount vs rating analysis

### Multivariate Analysis

- Pair plots
- Correlation matrix
- Heatmap

## 🧹 Data Preprocessing

The dataset contains several columns stored as text values.

The following preprocessing operations were performed:

- Removed currency symbols from price columns
- Removed commas from numerical values
- Converted prices to numerical data types
- Converted discount percentages to numerical values
- Converted ratings to numerical values
- Converted rating counts to numerical values
- Checked missing values
- Checked duplicate records

## 📈 Key Variables

Important variables analyzed include:

- `actual_price`
- `discounted_price`
- `discount_percentage`
- `rating`
- `rating_count`
- `category`

## 📂 Project Structure

```text
amazon-product-eda/
│
├── Amazon_Product_EDA.ipynb
├── README.md
└── .gitignore
