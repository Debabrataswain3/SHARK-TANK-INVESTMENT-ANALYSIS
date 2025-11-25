Below is a **clean, professional, GitHub-ready README** for your project.
It matches your dashboard, KPIs, workflow, and insights.

---

# 🦈 **Shark Tank Investment Analysis (Python + Tableau)**

## 📌 **Project Objective**

Analyze investment patterns in **Shark Tank India** using Python and Tableau.
The goal is to understand **startup funding trends, founder behavior, investor preferences, and domain-wise performance**, and present it through a **fully interactive Tableau dashboard**.

---

## 📁 **Dataset Used**

Dataset: *Shark Tank India – Investment Data (Cleaned)*
📄 Dataset Link: *(https://github.com/Debabrataswain3/SHARK-TANK-INVESTMENT-ANALYSIS/blob/main/shark_tank_dataset.csv)*
Example format:

```
Your cleaned dataset file:
`/mnt/data/sharktank_clean_dataset.csv` *(use this when uploading)*

---

## 🔍 **Key Business Questions**

1. **How much total funding was raised across seasons?**
2. **What is the average equity offered by startups?**
3. **Which domains receive the highest funding?**
4. **Which investors fund the most startups?**
5. **How does funding amount relate to equity offered?**
6. **How many startups appear per season?**
7. **What is the distribution of founders per startup?**

---

## 📊 **KPIs (Key Performance Indicators)**

Displayed at the top of the Tableau dashboard:

### 1️⃣ **Total Funding Amount**

→ SUM(Funding Amount)

### 2️⃣ **Average Equity Offered**

→ AVG(Equity Offered)

### 3️⃣ **Total Startups**

→ COUNTD(Startup Name)

### 4️⃣ **Funded Startups Count**

→ COUNTD(Startup Name WHERE Deal Status = “Funded”)

---

## 🛠 **Project Workflow (Python + Tableau)**

### ✔ Step 1 — **Data Cleaning (Python)**

* Removed duplicates
* Standardized text (lowercase, trim spaces)
* Cleaned categories (domain, investor, country, stage)
* Converted numeric fields to proper types
* Filled missing values:

  * Categorical → `"Unknown"`
  * Funding/Equity (for rejected deals) → `0`
* Treated outliers with IQR detection (but retained values for real-world patterns)

### ✔ Step 2 — **Exploratory Data Analysis (EDA)**

Using Pandas, Seaborn, Matplotlib:

* Distribution of funding
* Funding vs. equity scatter plot
* Domain-wise startup count
* Investor participation patterns
* Season-wise startup analysis
* Founder count histogram

### ✔ Step 3 — **Interactive Dashboard (Tableau)**

Dashboard contains:

#### 📌 **1. KPI Cards**

* Total Funding
* Average Equity %
* Total Startups
* Funded Startups

#### 📌 **2. Season-wise Startup Count (Line Chart)**

Shows how startup participation changed across seasons.

#### 📌 **3. Funding by Domain (Horizontal Bar Chart)**

Ranks domains by total raised funding.

#### 📌 **4. Deal Status by Investor (Stacked Bar Chart)**

Compares funded, rejected, and withdrawn deals for each shark.

#### 📌 **5. Funding vs Equity Offered (Scatter Plot)**

Shows how negotiation impacts deals.

#### 📌 **6. Founder Count Distribution (Bar Chart)**

Shows frequency of:

* Solo founders
* 2 founders
* 3 founders
* 4 founders

#### 📌 **7. Filters (Interactive)**

Users can filter by:

* Investor
* Stage
* Country

---

## 📈 **Dashboard Link**

*(Upload your Tableau Public Dashboard and paste link here)*
Example:

```
https://public.tableau.com/views/SharkTankInvestmentAnalysis/MainDashboard
```

---

## 🧠 **Project Insights**

### ✔ **1. Total Funding Exceeded ₹246 Crores**

Investors funded startups aggressively across categories.

### ✔ **2. Average Equity Offered ~ 11%**

Startups gave moderate equity for investment, showing strong valuations.

### ✔ **3. Top Funded Domains**

* Tech
* Agri
* FinTech
* Food

These domains consistently attracted the highest funding amounts.

### ✔ **4. Investor Activity Patterns**

* Some sharks prefer early-stage/low equity deals.
* “No Deal” outcomes were common for certain investors.
* A few investors dominated funded deals.

### ✔ **5. Strong Season Growth**

Season 1 → Season 2 → Season 3 showed rapid growth in startup participation.

### ✔ **6. Founders Per Startup**

Most startups had **2 or 1 founder**, showing typical early-stage team sizes.

### ✔ **7. Funding vs Equity Pattern**

Higher funding amounts do **not always** require more equity — indicating:

* Negotiation strength
* Profitability
* Valuation confidence

---

## ✅ **Final Conclusion**

This project provides a **complete end-to-end analytical workflow** covering data cleaning, advanced EDA, and interactive dashboard building.

It highlights:

* Funding trends
* Investor behavior
* Domain performance
* Founder team structures

The interactive dashboard helps entrepreneurs, analysts, and investors quickly understand **where money flows**, **which domains perform best**, and **what factors influence funding decisions**.

---
