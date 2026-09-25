# 🍔 Food Delivery Order Analysis

## 📊 Project Overview

**Food Delivery Order Analysis** is a data analytics project focused on transforming raw food delivery order data into reliable and actionable business insights.

The project covers **Data Cleaning, Exploratory Data Analysis (EDA), and Business Intelligence** to understand:

- 📈 Demand patterns
- 🏪 Restaurant performance
- 💰 Revenue and order value
- 🚴 Delivery efficiency
- ⭐ Customer experience
- ❌ Order cancellations and rejections

The project uses **Python, Pandas, NumPy, Matplotlib, and Seaborn** for data preparation, analysis, and visualization.

---

## 🎯 Problem Statement

Raw food delivery data can contain missing values, inconsistent formats, incorrect data types, duplicate records, and unstructured operational information.

The objective of this project is to clean and transform the raw dataset into a reliable analytical layer that can support business decisions related to **operations, customers, restaurants, revenue, and delivery efficiency**.

---

## 📁 Dataset

The dataset contains:

- **21,321 orders**
- **29 columns**

### Main Data Categories

| Category | Information |
|---|---|
| Core Fields | Order, restaurant, status, time, location, category |
| Commercial Fields | Subtotal, discounts, total, rating |
| Operations Fields | Distance, KPT duration, rider wait time |
| Experience Fields | Complaints, cancellation/rejection reasons |

### Data Challenges

The dataset contains several data-quality challenges:

- Missing values
- Inconsistent text
- String-based dates
- Distance values such as `<1km`
- Duplicate records
- Incomplete customer/delivery information

---

## 🔄 Project Workflow

```text
Raw CSV Data
     ↓
Data Understanding
     ↓
Data Cleaning
     ↓
Data Validation
     ↓
Feature Engineering
     ↓
Exploratory Data Analysis
     ↓
Insights & Decision Support
```

### 1. Data Understanding

Understanding the structure, columns, data types, and meaning of the raw dataset.

### 2. Data Cleaning

- Standardizing column names
- Removing unwanted spaces
- Handling missing values
- Removing/checking duplicates
- Converting dates into proper datetime format
- Converting distance values into numeric form

### 3. Data Validation

Validating numerical values and checking whether the cleaned dataset is reliable for analysis.

### 4. Feature Engineering

New analytical features are derived from the existing data:

- Year
- Month
- Day
- Hour
- Day Name
- Weekday / Weekend
- Time Period
- Is Delivered
- Is Non-Delivered
- Has Rating

> **Note:** Missing values are not automatically treated as zero; they are handled according to their business meaning.

---

## 🔍 Exploratory Data Analysis

The EDA focuses on different business areas.

### 📈 Demand Analysis

Questions explored:

- When is demand highest?
- How does demand vary by hour?
- Which days have higher demand?
- How does demand differ by month?
- Weekday vs Weekend demand patterns

### 🏪 Restaurant & Category Performance

Analysis of:

- Restaurant performance
- Category demand
- Subzone demand

### 💰 Commercial Analysis

Analysis of:

- Order value
- Subtotal
- Discounts
- Total order amount

### 🚴 Operations Analysis

Analysis of:

- Delivery distance
- KPT duration
- Rider waiting time
- Order status
- Rejected and returned orders

### ⭐ Customer Experience

Analysis of:

- Customer ratings
- Complaints
- Cancellation/rejection reasons

---

## 📊 Data Visualization

The project uses different visualization techniques to understand patterns and trends:

- Bar Charts
- Line Charts
- Histograms
- Scatter Plots
- KPI-based visualizations

These visualizations help convert raw data into understandable business insights.

---

## 🛠️ Tech Stack

### Programming Language
- Python

### Libraries

```text
Pandas
NumPy
Matplotlib
Seaborn
```

### Tools

```text
Jupyter Notebook
Git
GitHub
```

---

## 💡 Business Decision Support

The cleaned and analyzed data can support decisions related to:

- Identifying peak demand periods
- Comparing restaurant performance
- Monitoring revenue and order patterns
- Understanding delivery efficiency
- Studying rejected and returned orders
- Understanding customer satisfaction
- Monitoring operational patterns

---

## 🚀 Future Scope

The project can be extended with:

### 🔮 Forecast & Segment

- Demand forecasting
- Customer segmentation
- Delivery-time prediction

### 📊 Interactive Analytics

- Interactive dashboard
- Real-time monitoring of important business metrics

### 🏪 Monitor & Recommend

- Restaurant monitoring
- Restaurant recommendation systems

---

## ⚠️ Current Project Status

The current project focuses on the **data preparation and analytical framework**.

The PPT identifies the actual insight sections as placeholders until the dataset is fully analyzed. Therefore, specific numerical findings or business conclusions are **not claimed in this README**.

---

## 👨‍💻 Author

**Rishi Raj Saini**

**College:** Arya College of Engineering

---

## ⭐ Project Goal

> **Transform raw food delivery data into reliable, understandable, and actionable business intelligence.**
