# Victoria-Housing-Finance-Analysis-Copy
An exploratory data analysis of Victorian housing loan commitments using Python, SQL and Power BI.


# Victoria Housing Finance Analysis (2020–2026)

### Exploring Housing Loan Commitments and Borrowing Trends in Victoria, Australia

---

## 1. Project Overview

This project explores new housing loan commitments in Victoria, Australia, from March 2020 to September 2026, using publicly available data from the Australian Bureau of Statistics (ABS).

The objective is to understand how housing finance patterns have changed over time by analysing loan commitment volumes, total loan values, average loan sizes and year-on-year growth trends.

The project uses Python for data cleaning, transformation and exploratory data analysis, followed by Microsoft Power BI for dashboard development and visual reporting.

## 2. What Inspired This Project

My interest in Victoria's housing finance market started with a simple observation during our search for a rental property.

While looking for houses to rent, I noticed that there seemed to be more properties advertised for sale than properties available for rent.

When I discussed this observation with my husband, he mentioned that house sales appeared to be increasing. This made me curious about what was happening in Victoria's housing market and how people were financing their home purchases.

My curiosity grew further when my husband and I visited a bank to open a joint account. During our conversation, the banking advisor asked whether we were interested in purchasing a home and explained the home loan options available, including competitive interest rates.

These everyday experiences raised several questions:

- How many people in Victoria are taking out new housing loans?
- Are housing loan commitments increasing or decreasing?
- How is the total value of housing loans changing over time?
- Are average loan sizes increasing?
- How do owner-occupier and investor borrowing patterns differ?
- What trends can historical housing finance data reveal?

Rather than relying only on observations and assumptions, I decided to investigate these questions using publicly available ABS data.

This project is my attempt to turn everyday curiosity into a structured, data-driven investigation.

## 3. Project Objectives

- Analyse new housing loan commitments across Victoria.
- Examine changes in loan commitment numbers and values.
- Calculate average loan size over time.
- Identify quarterly and year-on-year growth patterns.
- Compare owner-occupier and investor housing finance trends.
- Explore first-home buyer lending patterns.
- Present findings through visualisations and an interactive Power BI dashboard.

## 4. Tools and Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and transformation |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Microsoft Power BI | Dashboard development |
| Excel | Initial data inspection |
| GitHub | Project hosting and documentation |
| ABS | Official data source |

## 5. Data Source

The project uses publicly available Australian Bureau of Statistics (ABS) Lending Indicators data.

The selected datasets are:

- **Table 4:** Owner Occupier Housing Finance
- **Table 14:** Investor Housing Finance
- **Table 24:** First Home Buyer Housing Finance

**Geographical scope:** Victoria, Australia  
**Analysis period:** March 2020 – September 2026  
**Data frequency:** Quarterly

The analysis focuses on new housing loan commitments, excluding refinancing where specified by the selected ABS series.

## 6. Key Performance Indicators (KPIs)

The owner-occupier analysis includes:

| KPI | Description |
|---|---|
| New Loan Commitments | Number of new housing loan commitments |
| Total Loan Value | Aggregate value of new loan commitments |
| Average Loan Size | Total loan value divided by loan count |
| Quarter-on-Quarter Growth | Percentage change from the previous quarter |
| Year-on-Year Growth | Percentage change from the same quarter in the previous year |

## 7. Data Preparation and Analysis

The Python workflow includes:

1. Importing and inspecting ABS Excel workbooks.
2. Reviewing metadata and identifying relevant time-series IDs.
3. Selecting Victoria-specific housing finance series.
4. Extracting original data for loan counts and values.
5. Filtering the analysis period from 2020 to 2026.
6. Cleaning column names and converting data types.
7. Checking missing values and duplicate records.
8. Calculating average loan size.
9. Calculating quarterly and year-on-year growth rates.
10. Creating time-series visualisations.
11. Exporting cleaned data into CSV format.

## 8. Key Findings – Owner-Occupier Analysis

The initial owner-occupier analysis revealed several interesting patterns:

- New housing loan commitment numbers reached a peak of **33,632 in June 2021**.
- Loan commitment volumes fluctuated considerably between 2020 and 2026.
- Average loan size increased over the analysis period.
- In September 2026, the number of new loan commitments declined by approximately **11.88% year-on-year**.
- The total value of new loan commitments declined by approximately **8.82% year-on-year** in September 2026.
- Average loan size reached approximately **$669,490 in September 2026**.

These findings highlight that the number of new housing loan commitments and the average size of those commitments can move differently.

*Note: These findings relate to the owner-occupier dataset only. Investor and first-home buyer comparisons are planned for subsequent stages.*

## 9. Data Visualisation

The Python analysis includes:

- Housing loan commitment trends over time.
- Total housing loan value trends.
- Average loan size trends.
- Year-on-year loan count growth.
- Year-on-year loan value growth.

The Power BI dashboard presents the findings through KPI cards, charts and a Victoria-focused geographical view.

## 10. Business Questions

This project aims to investigate practical questions relevant to the housing finance sector:

- How has housing borrowing activity changed over time?
- Are borrowers committing to larger loan amounts?
- How does investor borrowing compare with owner-occupier borrowing?
- What proportion of housing finance activity relates to first-home buyers?
- Which periods experienced the strongest growth or decline?
- What changes are visible in the latest available data?

## 11. Repository Structure

```text
Victoria-Housing-Finance-Analysis/
│
├── Victoria_Housing_Analysis.ipynb
├── victoria_housing_loans_cleaned.csv
├── Victoria_Housing_Finance_Dashboard.pbix
└── README.md
```

Additional investor and first-home buyer cleaned datasets will be added as their analyses are completed.

## 12. Important Notes and Limitations

- ABS new loan commitment data represents new housing finance commitments, not completed property purchases or settled loans.
- Average loan size is calculated by dividing total loan commitment value by the number of commitments. It does not represent the average property purchase price.
- The geographical scope covers Victoria as a state, not individual suburbs or Melbourne alone.
- Changes in loan commitments do not independently establish the reasons behind movements in property prices, rental availability or housing demand.
- The analysis is descriptive and does not establish causation.
- The initial findings are based on original quarterly data, not seasonally adjusted or trend data.

## 13. Future Enhancements

- Complete investor housing finance analysis.
- Analyse first-home buyer lending trends.
- Compare owner-occupier, investor and first-home buyer patterns.
- Combine cleaned datasets into a consolidated analytical model.
- Add further KPIs and interactive Power BI filters.
- Develop additional business insights from the combined datasets.

### Power BI Dashboard Preview

<img width="1920" height="1039" alt="dashboard_preview" src="https://github.com/user-attachments/assets/d5e466c4-c156-43d5-8160-efb9635f71a2" />



## 14. Project Outcome

This project demonstrates an end-to-end data analytics workflow, from identifying a real-world question and sourcing public data to cleaning datasets, calculating KPIs, exploring trends and presenting insights through visualisations and business intelligence reporting.

It also reflects my interest in using data to investigate everyday economic and financial questions.

---

**Data Source:** Australian Bureau of Statistics (ABS) – Lending Indicators.

**Project Period:** 2020–2026.

**Author:** Personal Data Analytics Portfolio Project.

