
# 📊 iPhone Sales Analysis in India

This project is an exploratory data analysis (EDA) of Apple iPhones listed on **Flipkart**, one of India's largest e-commerce platforms. The goal is to uncover insights into pricing, user ratings, discounts, and product popularity across various iPhone models.

---

![iPhone Sales Dashboard](https://github.com/kumarsahup07/iPhone-Sales-at-Flipkart-Analysis-Project-with-clean-data-/blob/main/iPhone%20Sales%20Insights%20in%20India.png?raw=true)

---

## 🗂️ Dataset

- **Filename:** `apple_products.csv`
- **Source:** Flipkart
- **Total Entries:** 62
- **Attributes:**
  - `Product Name`: Name of the iPhone model
  - `Product URL`: Flipkart product link
  - `Brand`: Product brand (all are Apple)
  - `Sale Price`: Actual selling price
  - `Mrp`: Maximum Retail Price
  - `Discount Percentage`: % difference between MRP and Sale Price
  - `Number Of Ratings`: Count of user ratings
  - `Number Of Reviews`: Count of user reviews
  - `Upc`: Universal Product Code
  - `Star Rating`: Average customer star rating
  - `Ram`: RAM size (e.g., 2 GB, 4 GB)

---

## 🔧 Technologies Used

- **Languages:** Python 3.x
- **Libraries:**
  - `pandas`, `numpy`: Data manipulation
  - `matplotlib`, `seaborn`: Visualization (static)
  - `plotly.express`, `plotly.graph_objects`: Interactive visualizations

---

## 📈 Analysis Highlights

### 1. Top-Rated iPhones
- Filtered top 15 iPhones by `Star Rating`.
- Visualized most popular models based on user ratings.

### 2. Most Reviewed iPhones
- Analyzed `Number Of Reviews` for top-rated phones.
- Plotted models that generated the most engagement.

### 3. Sale Price vs. Number of Ratings
- Scatter plot with bubble size representing `Discount Percentage`.
- Color intensity indicates discount rate.
- Added regression trendline to examine correlation.

### 4. Discount % vs. Number of Ratings
- Scatter plot where bubble size and color represent `Sale Price`.
- Highlights customer attraction towards discounted phones.

---

## 📊 Sample Visualizations

- **Bar Charts** for ratings and reviews.
- **Bubble Charts** for analyzing multi-dimensional relationships.
- **Interactive Plots** using Plotly for better insights.

---

## 🧠 Key Insights

- High `Star Rating` models like iPhone 11 and iPhone SE see more customer engagement.
- A higher discount does not always correlate with more reviews or ratings.
- Some models maintain high engagement despite lower discount percentages.
- Price-sensitive behavior is evident through visual correlation.

---

## ✅ Future Enhancements

- Perform time-based trend analysis (if historical data is added).
- Add sentiment analysis using user reviews (if text data is available).
- Build a recommendation engine based on popularity and pricing.

---

## **Author**  
- **Priyanshu Kumar Sahu** - [GitHub Profile](https://github.com/kumarsahup07)


---

## **License**  
Licensed under the **CC License**.
