
# Unpaid Bills Analytics Dashboard

## Tools Used
- **Microsoft Excel**
- **Power BI** (Data Modeling, DAX, Visualizations)

## Project Type
**Data Analytics & Business Intelligence**

---

## 1. Project Objective
The objective of this project was to design and implement an interactive **Unpaid Bills Analytics dashboard** that provides clear visibility on:
- Customer outstanding amounts
- Aging structure
- Agency performance
- Month-over-month debt behavior

The dashboard supports **data-driven decision making**, enabling management to:
- Identify high-risk areas
- Track trends
- Optimize collection actions across agencies and divisions

---

## 2. Project Description
This project involved:
- Collecting, cleaning, analyzing, and visualizing unpaid bills data extracted from the company’s billing systems.

### Analysis Focus:
- Total unpaid amount
- Number of customers with outstanding bills
- Unpaid bills count
- Distribution of debt across commercial agencies
- Evolution of debt by aging category
- Top agencies contributing to unpaid amounts
- Month-over-month (MoM) performance and improvement opportunities

Using **Power BI**, I developed a fully automated dashboard that updates dynamically and allows users to interact with the data through filters and drilldowns.

---

## 3. Data Processing & Modeling

### Data Preparation in Excel:
- Cleaned customer billing records
- Removed duplicates, null values, and inconsistencies
- Created calculated fields (Days Past Due, Aging Buckets)
- Standardized agency and division names

### Power BI Data Model:
- **Fact Table:** Unpaid Bills (amount unpaid, customer details, agency, division, age group, dates)
- **Date Dimension:** Generated and linked through Invoice Date
- **DAX Measures:**
  - Total Unpaid
  - Customers with Unpaid Bills
  - Unpaid Bills Count
  - Month-over-Month Change %
  - MoM Improvement
  - Debt by Aging Buckets

This model enables accurate filtering, trend comparison, and cross-division analysis.

---

## 4. Dashboard Features & Insights

### A. Key Performance Indicators (KPIs)
Displayed at the top of the dashboard:
- **13M** Total Unpaid
- **152K** Customers with Unpaid Bills
- **371K** Unpaid Bills Count
- **0%** MoM Improvement (no improvement vs. last month)

These indicators give management a quick overview of financial risk.
![Dashboad view] (https://github.com/Leussa-Code/Power-BI-Projects/blob/main/Debt%20Analysis%20dashboard.png)
### B. Unpaid Bills by Agency
- Horizontal bar chart ranking agencies by unpaid bills count.
- Agencies with the highest backlog are immediately visible for targeted follow-ups.

### C. Aging Group Analysis
- Stacked bar chart showing unpaid amounts across age categories (0–30, 31–60, 61–90, >90 days).
- Identifies segments with the highest risk of default.

### D. Debt Distribution by Division
- Donut chart displaying total unpaid amounts by division (East, West, Center, South).
- Highlights operational performance of each division.

### E. Top Unpaid Agencies Table
- Ranked table showing:
  - Total unpaid
  - MoM change %
  - Ranking
- Enables leadership to prioritize agencies requiring stronger actions.

---

## 5. Findings & Interpretation

### Key Observations:
- Some agencies show significantly higher unpaid amounts → gaps in follow-up.
- Aging analysis reveals large debt in **61–90 days** and **>90 days** categories → potential bad debt risk.
- MoM performance shows **0% improvement** → need for aggressive collection strategies.

### Business Impact:
- Helps leadership allocate collection resources effectively
- Supports strategic decisions for revenue recovery
- Improves monitoring of agency/division performance
- Reduces financial risk by targeting high-risk debt buckets

---

## 6. Conclusion
This project demonstrates the ability to **clean, model, analyze, and visualize operational data using Excel and Power BI**.

The final dashboard:
- Enhances transparency
- Supports effective debt recovery strategies
- Updates automatically with new billing data for continuous monitoring
