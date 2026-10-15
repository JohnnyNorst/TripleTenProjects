# TripleTenProjects
# 📊 Data Analytics & Visualization Portfolio

> Educational projects in **Google Sheets**, **Power BI**, **Tableau**, **data visualization**, and **analytics** — turning raw data into clear, decision-ready insights.

![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Data Visualization](https://img.shields.io/badge/Data%20Visualization-4B8BBE?style=for-the-badge)
![Analytics](https://img.shields.io/badge/Analytics-6A5ACD?style=for-the-badge)

---

## 👋 About This Repository

Hi, I'm Jason Osagie. This repository is a collection of projects I built while learning and practicing data analytics. Each project follows the same workflow: **ask a question → clean the data → analyze → visualize → communicate findings.**

**What you'll find here:**
- Spreadsheet-based analysis with formulas, pivot tables, and dashboards in Google Sheets
- Interactive business dashboards in Power BI (DAX measures, data modeling)
- Story-driven visualizations in Tableau
- Written insights that explain *what the data says and why it matters*

---

## 🗂️ Projects at a Glance

| # | Project | Tool | Skills Demonstrated | Links |
|---|---------|------|---------------------|-------|
| 1 | **NYC AirBnB Data Analysis** | Google Sheets | Formulas, pivot tables, visualisations | [Folder](https://github.com/JohnnyNorst/TripleTenProjects/tree/5d67c494ee0fda83b8e19bf7bd7f8b04423e369d/Google%20Sheets%20AirBNB%20)|
| 2 | **Business Analytics** | Google Sheets | Data cleaning, formulas, pivot tables, cohort analysis | [Folder](https://github.com/JohnnyNorst/TripleTenProjects/tree/2ca775c12818bcec9574e85cb56c18b17ed00d97/Google%20Sheets%20Business%20Analytics%20) |
| 3 | **Superstore Analysis** | Tableau | Data modeling, calculated fields, interactive charts | [Folder](https://github.com/JohnnyNorst/TripleTenProjects/tree/a25aed8850182012fcb2735583d49f9cabc3ea70/Tableau%20Superstore%20Analysis%20) |
| 4 | **Return Rate Analysis** | Tableau | Calculated Fields, dashboard, story, interactive filters | [Folder](https://github.com/JohnnyNorst/TripleTenProjects/tree/e9cea061cb0fd411b30ba7b968627687aa0797e4/Tableau%20Return%20Rate%20) |
| 5 | **Shopify Analysis** | Power BI | DAX, Vizualation, Filters,Data Modeling | [Folder](https://github.com/JohnnyNorst/TripleTenProjects/tree/e9cea061cb0fd411b30ba7b968627687aa0797e4/Power%20BI%20Shopify) |


---

## 🔍 Featured Projects

### 1. NYC Airbnb Market Analysis — Google Sheets

**Project Goal:** Analyze Manhattan’s Airbnb vacation rental market to identify the most attractive neighborhoods and property sizes for investment, and estimate the revenue potential of top-performing listings.

**Dataset:** NYC Airbnb listings and calendar data, including neighborhood, number of bedrooms, reviews over the last 12 months, nightly adjusted prices, and availability.

**Approach:** Cleaned inconsistent neighborhood labels and missing bedroom values, then used spreadsheet formulas, pivot tables, and a bar chart to identify the top 10 neighborhoods and most popular property sizes. Used `IF` and `SUMIF` functions to calculate rental revenue over a 30-day period and estimate annual revenue for recommended listings.

**Key Insights:** One-bedroom apartments were the most popular property size, with 1,265 listings, followed by two-bedroom apartments (526) and studios (441). The analysis also identified neighborhood-specific property preferences and ranked recommended listings by revenue. The top-earning listing generated $29,940 during the 30-day sample, equivalent to an estimated $359,280 annually if that revenue rate remained consistent.

📁 [Project Folder](https://github.com/JohnnyNorst/TripleTenProjects/tree/81795f591e5bcd74341938b82cfe5aaede36fd50/Google%20Sheets%20AirBNB%20)

---

### 2. E-commerce Business Analytics — Google Sheets

**Project Goal:** Analyze e-commerce user activity to measure website conversion performance and understand customer retention over time, helping the business identify opportunities to improve purchases and customer engagement.

**Dataset:** Raw website activity logs containing user IDs, event types, product categories, brands, prices, and event dates. The dataset includes product page views, shopping cart activity, and purchase events.

**Approach:** Built a conversion funnel using unique user counts to measure progression from product views to purchases. Filtered purchase records, used pivot tables and spreadsheet formulas (`VLOOKUP`, `TEXT`, and `DATEDIF`) to identify first purchase dates and assign customers to monthly acquisition cohorts. Calculated cohort retention rates across subsequent months and organized the results into an executive summary.

**Key Insights:** The analysis framework measures how effectively website visitors convert into purchasers and how consistently customers return to make purchases over time. It segments customers into six monthly cohorts and tracks retention for up to four months after their initial purchase, helping identify potential conversion bottlenecks and trends in customer loyalty.

📁 [Project Folder](https://github.com/JohnnyNorst/TripleTenProjects/tree/9a5a79ddc3136cb6493c00fd377d5cf48dcf39db/Google%20Sheets%20Business%20Analytics%20)

---

### 3. Saving Superstore — Tableau

**Project Goal:** Analyze the Superstore’s sales, profitability, advertising opportunities, and product return rates to identify operational improvements and recommend strategies to increase profitability and prevent financial losses.

**Dataset:** Superstore orders and returns data, including product names, subcategories, customer information, geographic regions, order dates, shipping modes, sales, profits, and returned-item status.

**Approach:** Used Tableau to create visualizations comparing profit and loss across product categories, regions, and other dimensions. Analyzed underperforming products and subcategories, identified the most profitable state-and-month combinations for advertising, and calculated return rates by product and customer using a left join between the Orders and Returns tables.

**Key Insights:** The analysis identifies major profit centers and loss-making products, highlights the three subcategories to prioritize and discontinue, and pinpoints promising advertising opportunities based on monthly profits and a proposed advertising budget of 20% of profits. Return-rate analysis also helps identify products and customers associated with frequent returns, supporting data-driven decisions to improve profitability.


🔗 [View on Tableau Public](https://public.tableau.com/views/Sprint4SuperstoreAnalysis_17804462049890/Sheet7?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) · 📁 [Project Folder](https://github.com/JohnnyNorst/TripleTenProjects/tree/caa9356b6aef901b1dd99045034e30aa3c9ea6ca/Tableau%20Superstore%20Analysis%20)

---

## 🧰 Skills & Tools

| Category | Skills |
|----------|--------|
| **Spreadsheets** | Google Sheets, pivot tables, `QUERY`, `VLOOKUP`/`XLOOKUP`, array formulas, data validation, conditional formatting |
| **BI Platforms** | Power BI (Power Query, DAX, data modeling), Tableau (calculated fields, LOD, parameters, dashboards) |
| **Analytics** | Data cleaning, exploratory data analysis, KPI design, trend & cohort analysis, descriptive statistics |
| **Visualization** | Chart selection, dashboard layout, color theory, accessibility, data storytelling |
| **Other** | [SQL, Excel, Python, Git/GitHub — add whatever applies] |

---



## 📚 Data Sources

Datasets used in these projects come from publicly available or educational sources, including:

- [Kaggle](https://www.kaggle.com/datasets)
- [data.gov](https://data.gov/)
- [Google Dataset Search](https://datasetsearch.research.google.com/)
- [Add your own sources here]

Each project folder lists its specific dataset and license/terms where applicable.

---

## 📬 Let's Connect

- 💼 LinkedIn: [Jason Osagie](https://www.linkedin.com/in/jason-osagie-48248638/)
- 📧 Email: Osajay98@gmail.com
- 🌐 [Portfolio / Tableau Public](https://public.tableau.com/app/profile/jason.osagie/vizzes)

---

## 📝 License & Usage

These projects are for **educational and portfolio purposes**. Datasets belong to their original owners. Feel free to reference my work — please give credit.

---

⭐ *If you found something useful here, consider starring the repo!*
