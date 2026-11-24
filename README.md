# 🚗 Automotive Retail Data Analytics

### Vehicle Sales Performance Analysis & Interactive Dashboard Using Advanced Microsoft Excel

---

## 📌 1. Project Overview

The **Automotive Retail Data Analytics** project is an end-to-end sales data analysis and dashboard development project built using Advanced Microsoft Excel.

The project focuses on analyzing 5,000 vehicle sales records to understand business performance, customer purchasing behaviour, product preferences, revenue distribution, payment patterns, and regional sales performance.

The objective is to transform raw dealership sales data into structured information and meaningful business insights through data cleaning, data preparation, exploratory analysis, Pivot Tables, Pivot Charts, KPI tracking, and interactive dashboards.

Two interactive dashboards were developed to provide a consolidated view of automotive retail performance:

1. **Sales Analysis Dashboard** – Focuses on revenue, sales trends, payment methods, sales channels, and geographical performance.
2. **Customer & Product Analysis Dashboard** – Focuses on customer demographics, brand preferences, vehicle categories, fuel types, transmission, and popular models.

This project demonstrates the practical application of Excel-based data analytics to solve business-oriented problems and support data-driven decision-making.

---

## 🎯 2. Business Problem Statement

Automotive dealerships generate large amounts of transactional data across customers, products, sales executives, payment methods, and geographical locations.

However, raw sales records alone do not provide an immediate understanding of business performance.

Dealership management needs answers to important questions:

- Which vehicle brands generate the highest customer demand?
- Which vehicle categories contribute the most to total sales?
- What are the major customer purchasing preferences?
- Which payment methods are most commonly used?
- How effective are different sales channels?
- Which states contribute the highest sales value?
- How does sales performance change over time?
- Which vehicle models and colours are most popular?
- What business strategies can improve dealership performance?

This project addresses these questions by organizing, analyzing, and visualizing sales data through interactive Excel dashboards.

---

## 🎯 3. Project Objectives

The primary objectives of this project are:

1. **Sales Performance Analysis:** Evaluate total sales, average on-road price, and overall revenue performance.

2. **Customer Behaviour Analysis:** Understand customer demographics, gender distribution, and purchasing patterns.

3. **Product Performance Analysis:** Identify popular vehicle brands, models, vehicle types, fuel types, and transmission preferences.

4. **Payment Analysis:** Evaluate customer payment preferences across Loan, UPI, Card, and Cash.

5. **Regional Analysis:** Identify high-performing states and geographical sales distribution.

6. **Sales Channel Analysis:** Compare Walk-in, Online, and Referral sales performance.

7. **Trend Analysis:** Understand quarterly and yearly sales patterns.

8. **Interactive Reporting:** Develop dashboards that allow users to explore data through dynamic slicers and visualizations.

---

## 🛠️ 4. Tools & Technologies

| Tool / Feature   | Application                                          |
| ---------------- | ---------------------------------------------------- |
| Microsoft Excel  | Primary analytics and dashboard development tool     |
| Pivot Tables     | Data summarization and aggregation                   |
| Pivot Charts     | Graphical representation of business metrics         |
| Excel Slicers    | Interactive filtering and dashboard navigation       |
| Data Cleaning    | Standardization and preparation of raw data          |
| KPI Cards        | Displaying important business performance indicators |
| Dashboard Design | Organizing insights into interactive reports         |

**Core Skills Demonstrated:**

- Data Cleaning & Preparation
- Exploratory Data Analysis (EDA)
- Data Aggregation
- Business Intelligence Reporting
- Data Visualization
- Dashboard Development
- Analytical Thinking
- Business Insight Generation

---

## 📂 5. Repository Structure

The repository is organized into separate folders to maintain a structured and understandable project workflow.

```text
automotive-retail-data-analytics/
│
├── Analysis/
│   └── Analytical work and supporting analysis
│
├── Result/
│   └── Final dashboard outputs and results
│
├── clean_data/
│   └── Cleaned and processed sales dataset
│
├── raw_data/
│   └── Original vehicle sales dataset
│
└── README.md
    └── Project documentation
```

Each folder represents a different stage or deliverable of the analytical workflow.

---

## 📊 6. Dataset Description

The project uses an automotive dealership sales dataset containing **5,000 sales records and 27 columns**.

The dataset includes information related to transactions, customers, vehicle specifications, pricing, payment methods, sales executives, and dealership branches.

### Dataset Information

| Attribute     | Description                   |
| ------------- | ----------------------------- |
| Total Records | 5,000                         |
| Total Columns | 27                            |
| Time Period   | 2024–2026                     |
| Industry      | Automotive Retail             |
| Data Type     | Structured Transactional Data |
| Analysis Tool | Microsoft Excel               |

### Dataset Attributes

The dataset contains the following major categories:

**A. Transaction Information**

- Sale_ID
- Sale_Date

**B. Customer Information**

- Customer_ID
- Customer_Name
- Customer_Age
- Gender
- State

**C. Vehicle Information**

- Vehicle_Type
- Brand
- Model
- Variant
- Fuel_Type
- Transmission
- Engine_CC
- Color
- Manufacturing_Year
- Warranty_Years

**D. Pricing Information**

- Ex_Showroom_Price
- On_Road_Price
- Discount_Amount
- Final_Selling_Price

**E. Sales & Financial Information**

- Payment_Mode
- Finance_Amount
- Sales_Executive
- Branch_ID
- Branch_City
- Sales_Channel

These attributes enable analysis across financial, geographical, customer, and product-related dimensions.

---

## 🔄 7. Project Workflow & Methodology

The project follows a structured analytical workflow, starting from raw data collection and ending with interactive reporting.

### Step 1: Data Collection

- Imported the original automotive dealership sales dataset.
- Examined the available columns and data structure.
- Identified important business dimensions and measures.
- Reviewed customer, vehicle, transaction, and financial information.

### Step 2: Data Cleaning & Preparation

Data quality is essential for reliable analysis. The dataset was reviewed and prepared before creating analytical summaries.

Key cleaning activities included:

- Identifying duplicate records.
- Checking blank and missing values.
- Standardizing inconsistent category labels.
- Correcting inconsistent colour names.
- Preparing categorical fields for consistent analysis.
- Organizing the data for Pivot Table reporting.

**Data Standardization Example:**

| Original Value | Standardized Value |
| -------------- | ------------------ |
| MatteBlack     | Matte Black        |
| Matte Green    | Matte Green        |
| MatteGreen     | Matte Green        |

This helped ensure that identical categories were not treated as separate values during analysis.

### Step 3: Exploratory Data Analysis

Exploratory analysis was performed to understand the dataset and identify useful business patterns.

The analysis covered:

- Sales distribution by year and quarter.
- Sales performance by brand.
- Revenue contribution by vehicle category.
- Customer distribution by gender.
- Payment mode preferences.
- Sales channel contribution.
- Fuel type and transmission preferences.
- Regional sales performance.
- Popular vehicle models and colours.

### Step 4: Data Analysis Using Pivot Tables

Excel Pivot Tables were used to summarize the transactional dataset and calculate important business metrics.

Major analytical dimensions included:

- Brand
- Vehicle Type
- Model
- Fuel Type
- Transmission
- Payment Mode
- Sales Channel
- State
- Gender
- Sale Date

Pivot Tables helped convert thousands of transactional records into meaningful summaries for dashboard development.

### Step 5: Data Visualization

Pivot Charts were created to communicate analytical findings effectively.

Different visualizations were used to represent:

- Payment distribution.
- Sales channel contribution.
- Vehicle category distribution.
- Fuel type preferences.
- Brand performance.
- Quarterly sales trends.
- Popular vehicle colours.

### Step 6: Interactive Dashboard Development

Two dashboards were developed using Excel dashboard components.

Interactive slicers were added for:

- Brand
- Vehicle Type

The slicers were connected to relevant Pivot Tables so that users could filter the dashboards and explore different business segments.

---

## 📈 8. Key Performance Indicators (KPIs)

The following KPIs provide a high-level overview of dealership performance.

| KPI                      |             Value |
| ------------------------ | ----------------: |
| Total Sales Value        | ₹2,464.18 Million |
| Total Sales Transactions |             5,000 |
| Average On-Road Price    |         ₹5,04,940 |
| Vehicle Categories       |                 3 |

**Note:** Total sales value represents the sum of Final Selling Price. Average On-Road Price represents the average of the corresponding dataset field.

---

## 📊 9. Dashboard 1 – Sales Analysis

The first dashboard focuses on overall sales performance, revenue trends, payment methods, and sales channels.

### Key Areas of Analysis

**1. Sales Performance**

- Overall sales value.
- Total sales transactions.
- Average on-road price.
- Sales trends across different periods.

**2. Payment Mode Analysis**

- Loan
- UPI
- Card
- Cash

**3. Sales Channel Analysis**

- Walk-in
- Online
- Referral

**4. Regional Performance**

- Sales value across different states.
- Identification of high-performing regions.

**5. Quarterly Sales Analysis**

- Comparison of quarterly performance.
- Identification of peak and low-performing quarters.
- Year-over-year sales patterns.

### Dashboard Insights

- Loan was the leading payment method, accounting for 2,620 transactions.
- Walk-in was the leading sales channel with 2,827 transactions.
- Q4 recorded the highest quarterly sales value in both 2024 and 2025.
- Maharashtra was the leading state by sales value.

---

## 👥 10. Dashboard 2 – Customer & Product Analysis

The second dashboard focuses on customer preferences and vehicle product performance.

### Key Areas of Analysis

**1. Brand Analysis**

Compare customer distribution across automotive brands to identify popular manufacturers.

**2. Vehicle Type Analysis**

Understand the distribution of:

- Bikes
- Cars
- Scooters

**3. Fuel Type Analysis**

Evaluate customer preferences across:

- Petrol
- Electric
- Diesel
- CNG

**4. Transmission Analysis**

Compare:

- Manual
- Automatic

**5. Model Analysis**

Identify the most popular vehicle models based on customer counts.

**6. Colour Preference Analysis**

Understand customer preferences for different vehicle colours.

### Dashboard Insights

- Honda recorded the highest customer count with 877 customers.
- Hero followed with 657 customers.
- TVS recorded 633 customers.
- Petrol vehicles accounted for 4,060 transactions.
- Manual transmission accounted for 3,047 transactions.
- Activa 6G was the most popular model with 214 customers.
- Black was the most preferred colour with 1,187 customers.

---

## 🔍 11. Detailed Business Insights

The analysis generated several meaningful findings across different business dimensions.

### A. Payment Mode Distribution

| Payment Mode | Transactions |    Share |
| ------------ | -----------: | -------: |
| Loan         |        2,620 |    52.4% |
| UPI          |          930 |    18.6% |
| Card         |          883 |    17.7% |
| Cash         |          567 |    11.3% |
| **Total**    |    **5,000** | **100%** |

**Observation:** More than half of the transactions were completed through loans, indicating the importance of financing options in vehicle purchases.

### B. Sales Channel Performance

| Sales Channel | Transactions |    Share |
| ------------- | -----------: | -------: |
| Walk-in       |        2,827 |   56.54% |
| Online        |        1,190 |   23.80% |
| Referral      |          983 |   19.66% |
| **Total**     |    **5,000** | **100%** |

**Observation:** Walk-in sales dominate the dealership's sales distribution, while Online and Referral channels provide additional opportunities for growth.

### C. Vehicle Type Distribution

| Vehicle Type | Transactions |    Share |
| ------------ | -----------: | -------: |
| Bike         |        1,927 |   38.54% |
| Car          |        1,693 |   33.86% |
| Scooter      |        1,380 |   27.60% |
| **Total**    |    **5,000** | **100%** |

**Observation:** Bikes contribute the largest share of transactions, followed by cars and scooters.

### D. Fuel Type Distribution

| Fuel Type | Transactions |    Share |
| --------- | -----------: | -------: |
| Petrol    |        4,060 |   81.20% |
| Electric  |          394 |    7.88% |
| Diesel    |          301 |    6.02% |
| CNG       |          245 |    4.90% |
| **Total** |    **5,000** | **100%** |

**Observation:** Petrol vehicles dominate the dataset, while electric vehicles represent the second-largest fuel category.

### E. Transmission Preference

| Transmission | Transactions |    Share |
| ------------ | -----------: | -------: |
| Manual       |        3,047 |   60.94% |
| Automatic    |        1,953 |   39.06% |
| **Total**    |    **5,000** | **100%** |

**Observation:** Manual transmission vehicles account for a higher share of transactions than automatic vehicles.

### F. Top Brands by Customer Count

| Brand | Customers |
| ----- | --------: |
| Honda |       877 |
| Hero  |       657 |
| TVS   |       633 |

**Observation:** Honda leads the customer distribution, followed by Hero and TVS.

### G. Most Popular Vehicle Colours

| Colour | Customers |
| ------ | --------: |
| Black  |     1,187 |
| White  |       954 |
| Red    |       705 |
| Blue   |       634 |
| Grey   |       623 |

**Observation:** Black is the most preferred colour among customers in the dataset.

### H. Top Brands by Finance Amount

| Brand         |  Finance Amount |
| ------------- | --------------: |
| Maruti Suzuki | ₹250.06 Million |
| Tata          | ₹228.43 Million |
| Mahindra      | ₹128.91 Million |
| Hyundai       | ₹128.36 Million |
| Toyota        |  ₹83.61 Million |
| Honda         |  ₹78.18 Million |

**Observation:** Maruti Suzuki leads in total finance amount, followed by Tata.

---

## 🧠 12. Challenges Faced & Solutions Implemented

During the analysis and dashboard development process, several data and visualization challenges were addressed.

| Challenge                        | Solution                                          |
| -------------------------------- | ------------------------------------------------- |
| Inconsistent category labels     | Standardized colour and category names            |
| Duplicate and blank records      | Reviewed and cleaned the dataset                  |
| Too many vehicle models          | Used Brand and Vehicle Type slicers for filtering |
| Sales data across multiple years | Grouped dates by Year, Quarter, and Month         |
| Multiple Pivot Tables            | Connected slicers to relevant Pivot Tables        |
| Dashboard consistency            | Maintained a consistent visual theme              |

These improvements helped make the analytical reports more consistent, readable, and interactive.

---

## 💡 13. Business Recommendations

Based on the analytical findings, the following business recommendations can be considered.

### 1. Strengthen Digital Sales Channels

Walk-in sales contribute approximately 57% of transactions.

Dealerships can explore improvements in online marketing, digital enquiries, and referral programs to increase the contribution of non-walk-in channels.

### 2. Improve Financing Opportunities

With approximately 52% of transactions made through loans, dealerships can consider:

- Partnerships with financial institutions.
- Attractive EMI options.
- Faster loan approval processes.
- Customer-friendly financing schemes.

### 3. Optimize Inventory Planning

Petrol vehicles represent approximately 81% of transactions.

Inventory planning can consider historical customer demand, vehicle categories, popular models, and colour preferences.

### 4. Focus on High-Performing Brands

Honda, Hero, and TVS have strong customer counts in the dataset.

Dealerships can use brand-level performance analysis to support stock allocation and promotional planning.

### 5. Strengthen Regional Sales Strategies

Maharashtra leads the dataset in sales value.

Regional marketing, customer engagement, and inventory strategies can be tailored according to geographical performance.

### 6. Monitor Quarterly Sales Trends

Q4 recorded strong sales values in 2024 and 2025.

Dealerships can study seasonal demand patterns and plan marketing campaigns and inventory accordingly.

---

## 📚 14. Key Learnings & Skills Developed

This project provided practical experience in applying data analytics techniques to a business-oriented dataset.

### Technical Learnings

- Understanding structured transactional datasets.
- Cleaning and preparing raw sales data.
- Standardizing inconsistent categorical values.
- Creating and managing Pivot Tables.
- Developing Pivot Charts.
- Building interactive dashboards using Slicers.
- Calculating and presenting business KPIs.
- Performing comparative and trend analysis.

### Analytical Learnings

- Converting raw records into meaningful information.
- Identifying customer purchasing patterns.
- Understanding sales channel performance.
- Evaluating product and brand preferences.
- Identifying regional and quarterly trends.
- Translating analytical results into business recommendations.

### Professional Skills

- Problem-solving
- Critical thinking
- Business understanding
- Data storytelling
- Analytical reporting
- Dashboard presentation

---

## 🚀 15. Future Scope & Improvements

The project can be extended through additional analytical features and reporting improvements.

Potential future enhancements include:

- More detailed customer segmentation.
- Advanced geographical sales comparisons.
- Deeper brand and model profitability analysis.
- Customer age-group purchasing analysis.
- Additional sales performance KPIs.
- More detailed year-over-year comparisons.
- Enhanced dashboard navigation and visualization.
- Automated reporting and data refresh workflows.

These improvements can provide deeper insights and support more advanced automotive retail analytics.

---

## 📸 16. Project Deliverables

The repository contains the following project components:

- Original raw sales dataset.
- Cleaned and prepared sales dataset.
- Supporting analytical work.
- Sales Analysis Dashboard.
- Customer & Product Analysis Dashboard.
- Project documentation.

**Dashboard Preview:** Add screenshots of the two completed dashboards in this section to provide a visual overview of the project.

---

## 👨‍💻 17. Author

### Abhinav Lowanshi

**Aspiring Data Analyst | Excel | Data Analytics | Dashboard Development**

I am interested in transforming raw data into meaningful insights and building analytical solutions that support business decision-making.

**Connect with me:**

- GitHub: [@abhinavlowanshi04-svg](https://github.com/abhinavlowanshi04-svg)
- Project Repository: [Automotive Retail Data Analytics](https://github.com/abhinavlowanshi04-svg/automotive-retail-data-analytics)

---

## ⭐ 18. Acknowledgement

This project was developed as a practical demonstration of data cleaning, analysis, and interactive dashboard development using Microsoft Excel.

The project highlights how structured data analysis and visualization can help transform raw automotive sales records into actionable business insights.

---
