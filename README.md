# 🛒 AMAZON SALES DATA ANALYSIS
**(EDA + Review Analysis)**

---

## 📖 Project Overview
This project performs Exploratory Data Analysis (EDA) on Amazon Sales data to uncover insights about product categories, pricing, customer behavior, and ratings.  
The analysis involves data cleaning, preprocessing, visualization, and statistical exploration to better understand sales performance and business drivers.

---

## 📝 Interactive Notebook
View the full interactive notebook with visualizations on Kaggle:  

[![Kaggle Notebook](https://img.shields.io/badge/Kaggle-Notebook-blue)](https://www.kaggle.com/code/amangarg08/amazon-sales-eda)

---

## 🎯 Objectives
- Clean and preprocess raw sales data  
- Handle missing values, duplicates, and inconsistent entries  
- Perform univariate, bivariate, and multivariate analysis  
- Create meaningful visualizations for better storytelling  

---

## 🗂 Dataset Features
- `product_id` : Product ID  
- `product_name` : Name of the Product  
- `category` : Category of the Product  
- `discounted_price` : Discounted Price  
- `actual_price` : Actual Price  
- `discount_percentage` : Percentage of Discount  
- `rating` : Product Rating  
- `rating_count` : Number of reviewers  
- `about_product` : Product description  
- `user_id` : Reviewer ID  
- `user_name` : Reviewer name  
- `review_id` : Review ID  
- `review_title` : Short review  
- `review_content` : Long review  
- `img_link` : Product image URL  
- `product_link` : Official product link  

---

## 📈 EDA Workflow
1. **Data Understanding**  
   - Load dataset, explore features and statistics  

2. **Data Cleaning & Preparation**  
   - Handle missing values, duplicates  
   - Data type conversions  
   - Outlier detection  

3. **Univariate Analysis**  
   - Distribution of ratings and discount percentage  
   - Most frequent product categories  
   - WordCloud for keywords in product name  

4. **Bivariate Analysis**  
   - Discount % vs sales (`rating_count`)  
   - Actual price vs discounted price correlation  
   - Ratings vs popularity  

5. **Multivariate Analysis**  
   - Feature correlations  
   - Categories balancing ratings, discounts, popularity  

6. **Review Analysis**  
   - Explore customer reviews for common words and sentiments  

7. **Key Insights & Observations**  

8. **Conclusion & Outcomes**  

---

## 💡 Key Insights

### Price
- Most products priced between 0–25,000 (affordability matters)  
- Price has weak correlation with ratings  

### Products
- Ratings mostly between 4–4.5  
- Black products ordered most, then white  
- Smart Watches & Charging Cables most popular  
- Top product: Fire-Boltt Ninja Call Pro Plus Smart Watch  

### Discount Percentage
- Most products have 50–60% discount  
- Discount % and rating/sales have very weak negative correlation  

### Ratings & Review
- High ratings ≠ high popularity  
- Frequent review terms: good, product quality, price, delivery, usability  

---

## 🏆 Outcomes
- Cleaned dataset prepared for analysis  
- Visual insights created for business strategy  
- Actionable insights on pricing, discounts, ratings, and categories  
- Ready for predictive modeling (sales forecasting, recommendation systems)  

---

## 🛠 Tools & Libraries
- **Language**: Python  
- **Libraries**:  
  - `pandas` – Data manipulation  
  - `numpy` – Numerical operations  
  - `matplotlib` & `seaborn` – Visualization  
  - `plotly` – Interactive graphs  
  - `scipy` – Statistical analysis  
  - `wordcloud` – Text visualization  
