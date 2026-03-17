# 📊 Airbnb Market Analysis — Vancouver

This project analyzes Airbnb listings in Vancouver to uncover pricing patterns, neighborhood trends, and factors influencing listing performance.

---

## 📌 Project Overview

The goal of this analysis is to answer key business questions such as:

- What is the average Airbnb price in Vancouver?
- Which neighborhoods are the most expensive?
- What types of listings are most common?
- How are price and customer engagement (reviews) related?

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Project Structure

    python-airbnb-market-analysis/
    │
    ├── airbnb_market_analysis.ipynb
    ├── README.md
    ├── data/
    │   └── airbnb_listings.csv
    └── images/
        ├── price_distribution.png
        ├── price_by_neighbourhood.png
        ├── room_type_distribution.png
        └── reviews_vs_price.png

---

## 🧹 Data Cleaning Process

The dataset required several preprocessing steps:

- Selected relevant columns for analysis
- Removed currency symbols from the price column and converted to numeric values
- Handled missing values:
  - Removed rows with missing prices
  - Replaced missing review data with 0
- Removed outliers (extreme prices above $1000)
- Reset index after filtering

---

## 📊 Key Visualizations

### 💰 Price Distribution

![Price Distribution](images/price_distribution.png)

---

### 🏙️ Price by Neighborhood

![Price by Neighbourhood](images/price_by_neighbourhood.png)

---

### 🛏️ Room Type Distribution

![Room Type Distribution](images/room_type_distribution.png)

---

### ⭐ Price vs Number of Reviews

![Reviews vs Price](images/reviews_vs_price.png)

---

## 📈 Key Insights

- The average Airbnb price in Vancouver is approximately **$150–$160 per night**
- Neighborhoods like **Downtown** and **Kitsilano** have the highest average prices
- The majority of listings are **entire homes/apartments**
- Most listings fall within the **$80–$200 price range**
- There is **no strong linear relationship** between price and number of reviews
  - Listings with more reviews tend to be in the mid-price range
  - High-priced listings generally receive fewer reviews

---

## 📦 Dataset

The dataset was sourced from:

https://insideairbnb.com/get-the-data/

*Note: The dataset may not be included in this repository due to file size.*

---

## 🎯 Purpose

This project was created as part of a **Data Analytics portfolio** to demonstrate:

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Data visualization
- Business insight generation

---

## 👤 Author

**Rayan Serratine**  
Data Analytics Portfolio  
📍 Vancouver, Canada
