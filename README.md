# ✈️ Global Airline Performance & Revenue Analysis

## 📌 Project Overview

The **Global Airline Performance & Revenue Analysis** project is an interactive **Power BI dashboard** designed to analyze airline operations, revenue, costs, profitability, passenger-class revenue, routes, and cost components.

The dashboard transforms airline operational and financial data into meaningful business insights that can help identify **revenue trends, cost drivers, profitable routes, passenger-class performance, and overall airline profitability**.

---

## 🎯 Objectives

* Analyze total flights and airline operational performance.
* Monitor total revenue, total cost, and total profit.
* Evaluate overall profit margin.
* Analyze monthly revenue and cost trends.
* Compare profitability across different routes.
* Analyze revenue generated from different passenger classes.
* Identify major airline cost components.
* Understand the relationship between operational activity, revenue, and profitability.
* Build an interactive and management-friendly Power BI dashboard.

---

## 🛠️ Tools & Technologies

* **Power BI**
* **Power Query**
* **DAX**
* **Data Modeling**
* **Data Visualization**
* **Excel / Structured Dataset**

---

## 📊 Dashboard KPIs

The dashboard tracks important airline business KPIs such as:

* ✈️ **Total Flights**
* 💰 **Total Revenue**
* 💸 **Total Cost**
* 📈 **Total Profit**
* 📊 **Profit Margin %**
* Business Class Revenue
* Economy Class Revenue
* First Class Revenue

---

## 📈 Key Dashboard Analysis

### 1. Overall Airline Performance

The dashboard provides a high-level overview of:

* Total number of flights
* Total revenue generated
* Total operational cost
* Total profit
* Overall profit margin

These KPIs provide a quick snapshot of the airline's financial and operational performance.

### 2. Monthly Revenue & Profitability Analysis

Monthly trends are analyzed to understand:

* Revenue growth and decline
* Changes in profitability
* Seasonal patterns
* High-performing and low-performing periods

### 3. Monthly Cost Analysis

The dashboard tracks monthly costs to identify periods with:

* Higher operational expenses
* Increasing cost trends
* Significant cost fluctuations

### 4. Route Profitability

Route-level analysis helps identify:

* High-profit routes
* Low-profit routes
* Revenue contribution by route
* Opportunities for route optimization

### 5. Passenger-Class Revenue Analysis

Revenue is analyzed across:

* **Economy Class**
* **Business Class**
* **First Class**

This helps understand which passenger segment contributes most to airline revenue.

### 6. Cost Component Analysis

The dashboard analyzes major cost components including:

* Airport Fees
* Catering Costs
* Crew Costs
* Fuel Costs
* Ground Handling
* Insurance
* Maintenance
* Delay Penalties
* Other Cost Adjustments

This analysis helps identify the major contributors to airline operating costs.

---

## 🧮 Important DAX Measures

Examples of important measures used in the project include:

```DAX
Total Revenue =
SUM(Cost_Details[Total revenue])
```

```DAX
Total Cost =
SUM(Cost_Details[Total Cost])
```

```DAX
Total Profit =
SUM(Cost_Details[Total Profit])
```

```DAX
Profit Margin % =
DIVIDE(
    [Total Profit],
    [Total Revenue],
    0
)
```

```DAX
Total Flights =
SUM(Cost_Details[Total Flight])
```

Additional measures were created for passenger-class revenue and cost analysis.

---

## 🔗 Data Model

The Power BI project contains three major analytical tables:

* **Cost_Details**
* **Flight_Operations**
* **Passenger_Revenue**

The model connects operational, financial, and passenger revenue information to support cross-table analysis.

---

## 🔄 Data Preparation

Power Query was used for data preparation activities such as:

* Data type validation
* Data cleaning
* Handling missing values
* Column transformation
* Creating analytical fields
* Preparing data for DAX calculations
* Structuring tables for Power BI modeling

---

## 💡 Business Insights

The dashboard can help airline management answer questions such as:

* How many flights were operated?
* How much revenue was generated?
* What is the airline's total profit?
* What is the current profit margin?
* Which months generated the highest revenue?
* Which routes are more profitable?
* Which passenger class contributes the most revenue?
* What are the major airline cost drivers?
* When do operating costs increase?
* Where are opportunities available to improve profitability?

---

## 📁 Project Structure

```text
Global-Airline-Performance-Analysis/
│
├── Global Airline.pbix
├── README.md
└── Dashboard/
    └── Global Airline Dashboard.png
```

---

## 🚀 Skills Demonstrated

This project demonstrates practical knowledge of:

* Power BI Dashboard Development
* Power Query
* DAX
* Data Modeling
* KPI Development
* Financial Analysis
* Revenue Analysis
* Cost Analysis
* Profitability Analysis
* Route Analysis
* Data Visualization
* Business Intelligence


## ⭐ Project Summary

A Power BI business intelligence project that analyzes **global airline operations, revenue, costs, profitability, routes, passenger-class performance, and cost components** through interactive KPIs and visualizations.
