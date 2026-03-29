# 🪔 Diwali Sales Data Analysis
**Uncovering Consumer Behavior & Strategic Retail Insights**

---

## 📌 Project Overview
This project involves a comprehensive **Exploratory Data Analysis (EDA)** of a Diwali sales dataset. By analyzing over 11,000+ transaction records, the study identifies purchasing patterns, high-value demographics, and product preferences to help businesses optimize inventory and marketing strategies for the festive season.

## 🎯 Key Objectives
* **Data Integrity:** Cleaning and preprocessing raw data for 11,000+ records.
* **Customer Profiling:** Analyzing spending power across Gender, Age Groups, and Marital Status.
* **Revenue Drivers:** Identifying top-performing states and occupations to focus marketing spend.

---

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** VS Code / Jupyter Notebook

---

## 🛠️ Technical Challenges & Solutions

### 1. Handling Null Values
* **Challenge:** The `Amount` column contained missing values that would have skewed revenue calculations.
* **Solution:** Performed targeted data cleaning by removing null rows to ensure the analysis was based on verified transactions.

### 2. Data Type Optimization
* **Challenge:** Currency values were loaded as floats, leading to cluttered visualizations.
* **Solution:** Converted the `Amount` column to integers using `.astype('int')` for better readability and faster computation.

### 3. File Encoding Issues
* **Challenge:** The raw CSV file used a non-standard encoding, causing "UnicodeDecode" errors during import.
* **Solution:** Resolved by applying `encoding='unicode_escape'` in the Pandas read function, ensuring data consistency.

---

## 📈 Key Insights & Findings

### 👥 Demographics
* **Gender:** Female customers significantly outspend male customers in both order volume and total value.
* **Age Group:** The **26–35 age bracket** (specifically married women) represents the highest purchasing volume.

### 📍 Geography & Occupation
* **Top States:** Uttar Pradesh, Maharashtra, and Karnataka lead in total revenue generation.
* **Spending Power:** Professionals in **IT, Healthcare, and Aviation** sectors have the highest disposable income during the festive season.

### 📦 Product Categories
* **Dominant Categories:** Clothing & Apparel, Food, and Electronics lead in sales.
* **Strategic Note:** While Clothing has the highest order count, Electronics contributes the most to the Average Order Value (AOV).

---

## 📌 Conclusion
The analysis confirms that the most profitable target segment for festive sales is **married women aged 26–35** residing in Tier-1 states. Businesses can maximize revenue by focusing inventory on Clothing and Electronics and targeting professionals in high-income sectors.

---

## 👤 Author
**Harsh Agrawal** *Data Analysis | Python | Business Intelligence*