# spinny-revenue-optimization

**Duration:** Jan 2025  
**Organization:** Nextleap (Capstone Project)  
**Role:** Data Analyst  
**Tools & Technologies:** Python (Pandas, NumPy, Matplotlib, Seaborn, SciPy), Tableau

---

## 📌 Project Objective

Spinny, a leading Indian startup in the pre-owned car space, aimed to increase revenue by optimizing car pricing and demand targeting.  
Using a dataset of **426,000+ used car transactions**, this project identifies key drivers of demand, optimal pricing ranges, and regional buying behavior to drive data-backed business decisions.

---

## 🎯 Goals

- Analyze demand by region, brand, and car attributes  
- Determine the most in-demand car models and combinations  
- Use Linear Regression to model and improve pricing  
- Drive revenue growth through data-backed recommendations  

---

## 🛠️ Key Techniques Applied

### 🔹 Data Wrangling & Cleaning
- Removed duplicates, irrelevant columns (VIN, image URLs)
- Imputed missing values (median, mode, bfill, ffill, domain logic)
- Fixed data types and standardized naming
- Outlier removal using IQR
- Created new columns: car_age, cylinders_count, etc.

### 🔹 Feature Engineering
- Min-Max scaling for normalization  
- Grouped states into income tiers  
- Calculated demand ratios by condition, region, and brand  

### 🔹 Exploratory Data Analysis (EDA)
- Heatmaps, barplots, histograms  
- Analyzed price vs mileage, region, condition, and fuel type  
- Compared buyer behavior across metro vs non-metro areas  

### 🔹 Hypothesis Testing
- ✅ Mileage negatively impacts price  
- ✅ Automatic cars have higher average prices  
- ✅ Region significantly affects conversion rates  
- ❌ State income doesn't correlate strongly with price

### 🔹 Machine Learning: Linear Regression
- Used Scikit-learn's Linear Regression for price prediction  
- Trained on features: age, odometer, fuel, transmission, brand  
- 📈 Insight: **Each extra cylinder adds ~₹46,400 to price**

---

## 📈 Key Findings

- South India had **38% higher conversion rates**  
- Cars with <50,000 km usage earn **₹50,000+ premium**  
- Automatic, 4-cylinder, diesel cars are most preferred  
- Target pricing: ₹0.5M–₹3M for maximum sales conversion  
- Regression coefficients revealed top predictors of price  

---

## 📊 Tableau Dashboard

▶️ [View Live Dashboard on Tableau Public](https://public.tableau.com/app/profile/guddu.singh8325/vizzes)

This interactive dashboard presents:
- 📍 State-wise demand heatmap  
- 🚘 Most demanding models by price, fuel type, and condition  
- 📈 Revenue trends by manufacturing year and transmission type  
- 🎯 Filters for region, brand, fuel, mileage, etc.

Enables business teams to:
- Identify high-performing car segments  
- Visualize demand trends across India  
- Set better pricing strategies by location and segment

---

## 📌 Business Recommendations

1. **Optimize Pricing:**  
   Use regression output to price low-mileage and high-cylinder cars at a premium.

2. **Target Inventory:**  
   Focus on automatic, 4-cylinder cars aged 3–8 years in good condition.

3. **Region Focus:**  
   Promote listings in Tier-1 cities and South India for higher conversion rates.

4. **Customer Segmentation:**  
   Customize offers for older or higher-mileage cars based on buyer behavior.

---

## 🧠 Learnings

- Built and interpreted Linear Regression models  
- Turned business questions into hypotheses and tested them with data  
- Strengthened skills in data cleaning, feature engineering, and dashboard design  
- Gained confidence in communicating insights through storytelling

---

## 📬 Contact

**📧 Email:** [guddu.binod.singh@gmail.com](mailto:guddu.binod.singh@gmail.com)  
**🔗 LinkedIn:** [linkedin.com/in/guddu1](https://www.linkedin.com/in/guddu1)  
**🌐 Portfolio:** [nextleap.app/portfolio/guddu-singh](https://nextleap.app/portfolio/guddu-singh)

---

