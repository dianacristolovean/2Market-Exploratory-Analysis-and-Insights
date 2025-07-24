# Customer Purchase Behaviour Analysis for 2Market
This was the first project I completed as part of the LSE Data Analytics Career Accelerator course

### Project Overview
This project is part of the LSE Data Analytics Career Accelerator and focuses on analysing customer demographics, purchasing behaviour, and advertising effectiveness for 2Market, a global supermarket chain. The goal was to extract actionable insights to support data-driven marketing strategies and optimize business performance.

### Objective
To explore customer behaviour and assess the performance of marketing channels, helping 2Market improve lead conversion, target high-value segments, and allocate resources more efficiently.

### Tech Stack Used
Excel – Initial data cleaning and exploratory analysis

PostgreSQL (PgAdmin 4) – Data validation and SQL querying

Tableau – Interactive dashboard design and visualization

### Background and Context
2Market sought to improve their understanding of customer purchasing patterns across demographics and marketing channels. 

The key business questions included:

* Which customer segments are the most profitable?

* How do purchasing habits differ by age, marital status, and education?

* Which marketing campaigns and channels are most effective?

Answering these questions helps 2Market optimize marketing spend, enhance customer segmentation, and improve campaign targeting—ultimately increasing profitability.

### Analytical Approach and Tools Used
Excel:
* Cleaned raw data by removing outliers, standardizing formats, correcting category anomalies, and ensuring consistency.
* Validated fields like age, income, and date to ensure data quality.

SQL (PgAdmin 4):
* Revalidated the data after importing into SQL tables.
* Used SQL queries to extract insights on sales by demographic, campaign effectiveness, and customer segmentation.

Tableau:
* Built three interactive dashboards:
  * Customer Demographics
  * Sales by Demographics
  * Campaign Analysis
* Applied best practices in design: clear layout, colorblind-friendly palette, and dynamic filters to support in-depth analysis.

### Key Findings and Insights
Demographics: 
* Most customers are aged 50–60, married, and highly educated.
* Customers from Spain dominate in both number and spending.

Sales Trends:
* Alcohol and meat products lead in popularity across most segments.
* Households with teenagers drive higher sales than those with younger kids.
* Higher education correlates with higher product spending.

Campaign Effectiveness:
* Social media campaigns (especially Twitter and Instagram) perform best, particularly among highly educated customers.
* Brochure and bulk mail campaigns underperform across all segments.
* Morocco, despite being a smaller market, shows high campaign success—suggesting potential for expansion.

### Dashboard Design
<img width="1366" height="768" alt="Sales by demographics" src="https://github.com/user-attachments/assets/a5fd5db8-1d4a-443c-97ca-fba4e0213caf" />
<img width="1366" height="768" alt="Demographics analysis" src="https://github.com/user-attachments/assets/ce8a73a9-1b30-4346-9815-546020d23557" />
<img width="1366" height="768" alt="Campaigns analysis" src="https://github.com/user-attachments/assets/0750d2a8-c9af-4b4b-ad3b-7b584fb1ccbd" />


Design Rationale:
* Blue tones chosen for readability and accessibility.
* Structured layout for logical navigation between demographics, sales, and campaign performance.
* Filters allow stakeholders to dynamically explore data by country, education, age group, and marital status.

### Challenges and Solutions
* Data quality issues such as inconsistent age and income entries, non-standard text fields, and outlier values were resolved through rigorous Excel cleaning and validation.

* SQL import errors and data inconsistencies were mitigated by thorough post-import checks (nulls, duplicates, invalid ranges).

* The original data lacked key metrics like purchase frequency and customer feedback, limiting some advanced segmentation. These were noted as areas for future data enrichment.

### Business Impact and Recommendations

* Increase marketing to high-income older customers (70–80 age group) who currently spend less despite high income.

* Promote family-oriented deals to married customers and households with kids.

* Develop affordable product lines and campaigns for the 30–40 age group to boost engagement.

* Target educated segments (Graduates, Masters, PhDs) with tailored messaging and premium product campaigns.

* Reallocate budget toward effective channels like Instagram and Twitter.

* Explore expansion in responsive markets like Morocco; reconsider or rework strategy for underperforming countries like the USA and Montenegro.



