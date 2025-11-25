Below is a **complete, polished, GitHub-ready README.md** for your project.

It includes:
✓ Project name
✓ Objective
✓ Dataset details + link (with your local file path)
✓ KPIs
✓ Analysis questions
✓ Process (Python + Tableau)
✓ Dashboard link (placeholder—add your Tableau Public URL)
✓ Insights
✓ Final conclusion

It is structured exactly the way employers expect.

---

# **SHARK TANK INVESTMENT ANALYSIS (Python + Tableau)**

## **📌 Project Objective**

Analyze and visualize investment trends from Shark Tank India/US startup data to understand funding behavior, investor patterns, domain profitability, and founder characteristics.
This project combines **Python (for data cleaning & EDA)** and **Tableau (for dashboard visualization).**

---

## **📂 Dataset Used**

Cleaned dataset used for this project:
`/mnt/data/sharktank_clean_dataset.csv`

(Replace this with your GitHub raw link when you upload.)

Dataset includes fields such as:

* Startup Name
* Domain
* Country
* Founders
* Funding Amount
* Equity Offered
* Deal Status
* Investor
* Stage
* Season

---

## **❓ Key Business Questions**

This analysis answers the following:

1. **Which industries/domains received the highest funding?**
2. **Which investors funded the most startups?**
3. **How does funding amount relate to equity offered?**
4. **What seasons had the highest number of startup pitches?**
5. **What is the distribution of founder team size (1 founder vs 2, 3, 4)?**
6. **Which deal statuses were most common across investors?**
7. **Which countries and stages dominate the pitch dataset?**

---

## **📊 Project KPIs**

Displayed on the dashboard:

* **Total Funding Amount**
* **Average Equity Offered (%)**
* **Total Startups**
* **Total Funded Startups**

---

## **🛠 Process & Methodology**

### **1. Data Cleaning (Python)**

* Handled missing values (categorical → "Unknown", numeric → median/0 based on logic)
* Standardized formats (country names, stages, investors)
* Converted fields to correct data types
* Treated outliers using visualization (boxplots, scatter plots)
* Exported final cleaned dataset `/mnt/data/sharktank_clean_dataset.csv`

### **2. Exploratory Data Analysis (Python)**

* Univariate analysis (distributions, histograms)
* Bivariate analysis (funding vs equity, founders vs deal status)
* Crosstab analysis for investor × deal-status behavior
* Industry-level funding comparison

### **3. Tableau Visualization**

Created a complete **interactive dashboard** including:

**KPI Cards:**

* Total Funding
* Avg Equity
* Total Startups
* Funded Startups

**Charts:**

* Season-wise Startup Count (Line Chart)
* Funding by Domain (Horizontal Bar Chart)
* Deal Status by Investor (Stacked Bar Chart)
* Funding vs Equity Offered (Scatter Plot)
* Founder Count Distribution (Histogram/Bar Chart)

**Filters added:**

* Investor
* Stage
* Country

---

## **📈 Tableau Dashboard Link**

**(Replace this after publishing)**
👉 *Your Tableau Public Dashboard Link Here*

---

## **🔍 Key Insights**

### **1. Funding Trends**

* Funding is dominated by a few top domains like **Tech, Food, Fashion, Logistics, Fintech**.
* Some industries receive consistently higher funding despite fewer startups.

### **2. Investor Behaviour**

* Certain sharks fund significantly more startups than others.
* The distribution of **Funded vs Rejected vs Partial** deals differs greatly by investor.
* A few investors are more aggressive (higher deal count), others more selective.

### **3. Season Trends**

* Number of startups pitched increases significantly in later seasons.
* Last season shows the **highest participation & highest funding intensity.**

### **4. Founder Team Sizes**

* Most startups have **2 founders**, showing a strong preference for team-based entrepreneurship.
* Single-founder startups are less common.

### **5. Funding–Equity Relationship**

* Higher funding does **not always** lead to higher equity dilution.
* Some outliers exist—large funding for low equity → indicates strong negotiation or strong product.

---

## **🧾 Final Conclusion**

This Shark Tank investment analysis highlights patterns in funding behavior, investor decisions, domain profitability, and founder dynamics.

By combining Python for deep data preparation and Tableau for interactive visualization, the project delivers:

* **Clear investment trends** across seasons and industries
* **Reliable insights** for entrepreneurs on what attracts funding
* **Investor profiles** showing risk appetite and deal preferences
* **Visual storytelling** that converts raw data into meaningful business decisions

This dashboard can be extended further to include **predictive modeling**, **investor recommendation systems**, and **startup scoring models**.

---

If you want, I can also generate:

✔ A polished **project cover image**
✔ A **GitHub description banner**
✔ A **PDF summary**
✔ A **video script** explaining the dashboard

Just tell me.
