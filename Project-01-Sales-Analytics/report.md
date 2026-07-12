# 📊 Sales Data Analysis Report

## 📌 Project Overview

This project analyzes one month of retail sales data using **NumPy**. The objective is to extract meaningful business insights from raw sales data using vectorized operations instead of traditional Python loops.

The project demonstrates fundamental NumPy concepts such as indexing, slicing, aggregation, boolean masking, sorting, and difference calculations while solving real-world business problems.

---

# 🎯 Objectives

- Calculate the total monthly revenue.
- Determine the average daily sales.
- Identify the highest and lowest sales days.
- Find the number of days with above-average sales.
- Compare weekend and weekday sales.
- Analyze daily sales growth.
- Evaluate sales target achievement.
- Filter sales within a specific range.
- Identify the Top 5 highest sales days.
- Generate a final business dashboard.

---

# 📂 Dataset Information

| Attribute | Description |
|-----------|-------------|
| Dataset Name | Monthly Sales Dataset |
| File Format | CSV |
| Total Records | 30 Days |
| Features | Day, Sales |

---

# 🛠 Technologies Used

- Python
- NumPy
- VS Code
- Git
- GitHub

---

# 📚 NumPy Concepts Covered

- Array Creation
- Reading CSV using `np.genfromtxt()`
- Indexing
- Slicing
- Aggregation Functions
  - `np.sum()`
  - `np.mean()`
  - `np.max()`
  - `np.min()`
- `np.argmax()`
- `np.argmin()`
- Boolean Masking
- Boolean Indexing
- Multiple Conditions (`&`, `|`)
- `np.diff()`
- `np.argsort()`
- Vectorized Operations

---

# 📈 Analysis Performed

## 1. Total Revenue Analysis

Calculated the total revenue generated during the month using `np.sum()`.

### Business Insight

This metric represents the company's overall monthly revenue and helps evaluate business performance.

---

## 2. Average Daily Sales

Calculated the average daily sales using `np.mean()`.

### Business Insight

Average sales provide a benchmark for comparing daily performance and identifying unusual sales trends.

---

## 3. Highest & Lowest Sales Analysis

Identified:

- Highest sales value
- Highest sales day
- Lowest sales value
- Lowest sales day

using:

- `np.max()`
- `np.min()`
- `np.argmax()`
- `np.argmin()`

### Business Insight

These metrics help identify the company's best and worst-performing days.

---

## 4. Above Average Sales Analysis

Counted the number of days where sales exceeded the monthly average.

### Business Insight

A higher number of above-average days indicates stable business performance.

---

## 5. Weekend vs Weekday Analysis

Compared weekend and weekday sales using Boolean Masking.

### Business Insight

This analysis helps determine customer purchasing behavior during weekends and weekdays.

---

## 6. Sales Growth Analysis

Calculated day-to-day sales growth using `np.diff()`.

### Business Insight

This analysis measures daily changes in sales and identifies business growth patterns.

---

## 7. Sales Performance Analysis

Calculated:

- Days with increased sales
- Days with decreased sales
- Days with no change

### Business Insight

Monitoring daily sales movement helps evaluate consistency in business performance.

---

## 8. Sales Target Analysis

Compared daily sales against a target of **₹3000**.

Calculated:

- Target achieved days
- Target missed days
- Sales values for each category

### Business Insight

Target achievement helps management evaluate overall sales performance and employee productivity.

---

## 9. Sales Range Analysis

Filtered sales between **₹2000** and **₹4000** using multiple Boolean conditions.

### Business Insight

Normal sales days provide a realistic picture of routine business performance.

---

## 10. Top 5 Best Sales Days

Used `np.argsort()` to identify the five highest sales days.

### Business Insight

These days may correspond to promotions, festivals, or seasonal demand and can guide future marketing strategies.

---

## 11. Business Dashboard

Created a final dashboard summarizing:

- Total Revenue
- Average Sales
- Highest Sales
- Lowest Sales
- Above Average Days
- Target Achievement
- Daily Sales Growth
- Best Performing Day

### Business Insight

A dashboard enables managers to understand overall business performance quickly without examining raw data.

---

# 💼 Skills Demonstrated

- Data Cleaning
- Data Exploration
- Business Analysis
- NumPy Programming
- Boolean Masking
- Vectorized Computation
- Statistical Analysis
- Problem Solving
- Code Documentation

---

# 📊 Key Business Insights

- Calculated the company's monthly revenue.
- Measured average daily sales performance.
- Identified the highest and lowest sales days.
- Determined the number of above-average sales days.
- Compared weekend and weekday performance.
- Evaluated daily sales growth trends.
- Measured sales target achievement.
- Filtered normal sales days.
- Ranked the Top 5 highest sales days.
- Generated a comprehensive business dashboard.

---

# 🎓 Learning Outcomes

After completing this project, the following NumPy concepts were mastered:

- Reading CSV files
- Array Indexing
- Array Slicing
- Aggregation Functions
- Boolean Masking
- Boolean Indexing
- Vectorized Operations
- Sorting Arrays
- Difference Calculations
- Business KPI Analysis

---

# 🚀 Future Improvements

Future versions of this project may include:

- Data Visualization using Matplotlib
- Interactive Dashboard using Plotly
- Data Analysis using Pandas
- Sales Forecasting
- Monthly Trend Analysis
- Customer Segmentation
- Export Reports as PDF
- Machine Learning-based Sales Prediction

---

# 🏁 Conclusion

This project demonstrates how NumPy can be used to efficiently analyze structured business data using vectorized operations. It provides valuable business insights without relying on traditional loops and establishes a strong foundation for advanced data analysis using Pandas, Matplotlib, and Machine Learning libraries.

The project also showcases practical problem-solving skills, clean coding practices, and business-oriented thinking, making it an excellent addition to a Data Science or Data Analytics portfolio.