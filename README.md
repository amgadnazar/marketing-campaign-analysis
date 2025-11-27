# Marketing Campaign Analysis --- Power BI & Python

*A complete end-to-end data analysis project using Python, Pandas, and
Power BI.*

## Project Overview

This project analyzes the performance of multiple marketing campaigns
using a real advertising dataset.\
The goal is to identify:

-   Which campaigns performed best\
-   Which audiences converted most efficiently\
-   Where budget was wasted\
-   What targeting strategies should be improved

The project includes:

-   Data cleaning & KPI creation in **Python**
-   Visualization & dashboard building in **Power BI**
-   Insights derived from CTR, CPC, CPM, and CPA metrics\
-   Exported dashboards and conclusions

## Tools & Technologies

-   **Python** (Pandas, NumPy)
-   **Jupyter Notebook**
-   **Power BI Desktop**
-   **CSV Dataset**
-   **GitHub** for project hosting

## Project Structure

    marketing-campaign-analysis/
    │
    ├── marketing_powerbi_ready.csv
    ├── marketing_dashboard.pbix
    ├── marketing_dashboard.png
    ├── analysis.ipynb
    └── README.md

## KPIs Calculated in Python

**Click-Through Rate (CTR)**\
`CTR = Clicks / Impressions`

**Cost per Click (CPC)**\
`CPC = Spent / Clicks`

**Cost per Mille (CPM)**\
`CPM = (Spent / Impressions) * 1000`

**Cost per Acquisition (CPA)**\
`CPA = Spent / Approved_Conversion`

These KPIs were added to the dataset and exported for Power BI
visualization.

##  Power BI Dashboard

The dashboard includes:

### **KPI Cards**

-   Total Spend\
-   Total Approved Conversions\
-   Average CPA\
-   Average CTR

### **Visuals**

-   **Average CPA by Age Group**\
-   **Average CPA by Gender**\
-   **CTR Trend by Age Group**\
-   **Spend vs Approved Conversions per Campaign**

## Power BI Dashboard

![Marketing Dashboard](marketing_dashboard.png)

### **Insights Summary**

-   Age group **30--34** performs best with the lowest CPA\
-   Age group **45--49** shows highest CPA despite higher CTR\
-   **Males** convert more efficiently than females\
-   Several campaigns spent money but produced **zero conversions**\
-   CTR increases with age, but conversion rate does not

## Dataset

The dataset contains the following key fields: - `ad_id`\
- `fb_campaign_id`\
- `age`\
- `gender`\
- `interest`\
- `Impressions`\
- `Clicks`\
- `Spent`\
- `Approved_Conversion`\
- Added KPIs: CTR, CPC, CPM, CPA

## Key Takeaways

-   Younger audiences (30--34) are the most cost-effective target
    group.\
-   Older audiences click more but convert less.\
-   Gender-based targeting shows that males deliver stronger conversion
    efficiency.\
-   Some campaigns need budget reallocation to avoid wasted spend.\
-   Data-driven decisions can significantly improve marketing ROI.

## Author

**Amjad Nazar**\
Data & Marketing Analyst\
Python • Power BI • Data Visualization

## If you like this project

Give the repository a ⭐ on GitHub and connect with me on LinkedIn!

## Portfolio
https://amgadnazar.github.io/
