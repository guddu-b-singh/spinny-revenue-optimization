# spinny-used-car-price-optimization

## End-to-end ETL, EDA, and price modeling project using Python, Scipy, and Tableau to optimize used car pricing for Spinny.


## 📌 Objective
Help Spinny improve its revenue and conversion rate by analyzing car listings and identifying price-performance trends.

## 🛠 Tools Used
- Python: Pandas, NumPy, Matplotlib, Seaborn, Scipy
- Tableau: Interactive dashboard
- Jupyter Notebook

## 🔁 Simulated ETL Process
**Extract**: Raw CSV dataset with over 400k used car listings 

**Transform**:
- Cleaned nulls, removed outliers using IQR
- Created features: `car_age`, `mileage_group`, `price_category`
- Grouped by brand, region, and km-driven for KPI extraction

**Load**:
- Cleaned and processed data exported to Tableau for dashboarding

## 📊 Key Analysis Areas
- Price vs Age
- Price vs Distance Driven
- Region-wise Price Trends
- Brand-wise Demand Segmentation

## 📈 Model: Linear Regression (Scipy)
Used `scipy.stats.linregress` to:
- Predict pricing based on car age and km driven
- Assess linear relationships with R² and p-values
- Evaluate impact of individual variables on pricing

## 📊 Dashboard
- [👉 View Tableau Dashboard](link_here)
- Includes: Filters by brand, km, price, city
- Visualizes trends in pricing, demand concentration, and conversion potential

## 🧠 Key Insights
- <50,000 km driven cars can be priced 8–12% higher
- South India had 38% higher conversion rate
- ₹0.5M–₹3M was the sweet pricing spot across brands

## ✅ What This Project Demonstrates
- End-to-end data wrangling and EDA
- Statistical modeling using Scipy (Regression)
- Visual storytelling using Tableau
- Business-focused insight generation

## 📌 Next Steps
- Add NLP on customer reviews to improve model with sentiment scores
- Automate ETL using Python scheduler (optional)
