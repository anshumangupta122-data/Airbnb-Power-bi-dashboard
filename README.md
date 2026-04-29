# 🌍 Global Airbnb Performance Dashboard

## 📊 Project Overview

This project delivers an end-to-end analysis of Airbnb’s global marketplace using an interactive dashboard built in Power BI.

The objective is to transform raw listings and reviews data into actionable insights that help understand:

* Market dominance across cities
* Customer engagement patterns
* Seasonal demand shifts
* Pricing competitiveness vs. hotels

This dashboard simulates a real-world business scenario where stakeholders need to monitor platform performance and optimize strategic decisions.

---

## 🎯 Business Problem

Airbnb operates across multiple cities with varying demand patterns, pricing strategies, and customer behaviors.

Key questions addressed:

* Which cities contribute the most to overall platform activity?
* How does customer engagement vary across time?
* What seasonal trends impact bookings and reviews?
* How does Airbnb pricing compare to traditional hotels?
* Are trust indicators (verified hosts, profiles) influencing engagement?

---

## 🚀 Key Features & Analysis

### 📈 Listings Growth Lifecycle

* Tracks Airbnb’s expansion phases:
  Introduction → Growth → Maturity → Decline → Reinvention → COVID Impact
* Helps understand macro-level business evolution

---

### 🌆 City-Level Market Share

* Compares contribution of cities like Paris, NYC, Rome, Sydney
* Identifies dominant and emerging markets

---

### 💰 Pricing Analysis

* Airbnb vs Hotel pricing comparison
* Highlights affordability and competitive positioning

---

### ⭐ Ratings & Customer Satisfaction

* Overall rating distribution
* Detailed breakdown:

  * Accuracy
  * Cleanliness
  * Communication
  * Location
  * Value

---

### 🔁 Review Frequency Analysis

* Analyzes customer engagement patterns
* Identifies repeat review behavior trends

---

### 📅 Seasonality Trends

* Monthly review distribution across cities
* Detects peak demand periods and off-season dips

---

### 🔐 Trust & Verification Insights

* Host verification rates
* Profile completeness impact on trust

---

## 🧠 Data Modeling & DAX (Core Strength)

* Built a **Star Schema**:

  * Fact Table: Reviews
  * Dimension Table: Listings

* Created advanced measures:

  * Total Reviews
  * % of Monthly Reviews (context-aware calculation)
  * Time-based aggregations

* Solved real-world challenge:

  * Fixed **filter context issue between Listings and Reviews**
  * Ensured correct city-wise contribution using DAX

---

## 🛠️ Tech Stack

* 📊 Microsoft Power BI (Data Modeling, DAX, Dashboarding)
*  Ms Excel
* 🗂️ Data Source – Airbnb dataset (public/simulated)
* 🔧 Git & GitHub – Version control

---

## 📂 Project Structure

```
📁 Airbnb-Dashboard
 ┣ 📊 Airbnb-Dashboard.pbix
 ┣ 📁 Data
 ┃ ┗ dataset.csv
 ┣ 📁 Images
 ┃ ┗ dashboard-preview.png
 ┗ 📄 README.md
```
## Key Insights

* Paris and NYC dominate review share across most months
* Peak activity observed during mid-year (summer season)
* Majority of users leave very few reviews → low repeat engagement
* Verified hosts significantly improve trust perception

---

## Future Enhancements

* Dynamic Top N city filtering
* Drill-down analysis (City → District → Listing)
* Integration with real-time data sources
* Advanced forecasting using time series models

---

## 💼 About Me

Aspiring Data Analyst with hands-on experience in Power BI, SQL, and data visualization.
Focused on solving business problems using data-driven insights.

---

