# 🏠 Real Estate Rental Price Analysis in Oman

This project simulates a real-world data science workflow focused on property rental listings in Oman. The goal is to scrape data from two real estate websites, clean and integrate the data, engineer meaningful features, and lay the groundwork for predictive modeling of rental prices.

## 🌐 Assigned Websites

- [Hilal Properties Oman](https://hilalprp.com.om/)
- [OpenSooq Oman](https://om.opensooq.com/)

Each website contains rental property listings that provide details like title, location, number of rooms, size, and price.

---

## 📌 Project Objectives

1. **Web Scraping**
   - Extract relevant property information:
     - Property title
     - Location
     - Price
     - Size (square meters)
     - Listing type
   - Handle pagination and dynamic content where necessary.
   - Save raw data from each site in CSV format.

2. **Data Cleaning & Integration**
   - Clean datasets using Python (handle missing values, inconsistent formats, and duplicates).
   - Standardize and merge both datasets into a unified, structured CSV.
   - Ensure consistent column naming conventions and data types.

3. **Feature Engineering**
   - Create new variables to support modeling:
     - `price_per_sqm`: Price divided by size.
     - `price_category`: Categorized price ranges.
     - Encoded categorical features.
   - Apply feature scaling using `StandardScaler`.

## 🛠️ Tools & Libraries

- Python
- BeautifulSoup & Requests (for web scraping)
- Pandas & NumPy (for data manipulation)
- Scikit-learn (for feature engineering and scaling)
- Jupyter Notebooks
