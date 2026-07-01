# Credit-Risk-Analysis---Nova-Bank
# Nova Bank Credit Risk Analytics

Power BI dashboard analyzing borrower risk across the USA, UK, and Canada using the Onyx Data September 2025 Monthly Dataset Challenge dataset.

## Project Overview

This project explores credit risk patterns in a 32,581 row lending dataset covering borrower demographics, loan details, and risk indicators. The goal was to build a decision ready dashboard that a credit risk team could use to identify high risk segments, monitor portfolio health, and support lending decisions.

## Business Problem

Nova Bank needed a clear view of where default risk was concentrated across its loan portfolio, which borrower segments carried the highest risk, and how risk varied by country. The dashboard answers three core questions:

- What is the overall default rate and portfolio at risk?
- Which borrower segments (income band, loan purpose, home ownership, employment length) show elevated risk?
- How does risk differ across the USA, UK, and Canada?

## Data Model

The report is built on a star schema with a central loan facts table connected to dimension tables for borrower demographics, loan details, and date. Key transformations were handled in Power Query, including data type corrections, column splitting, and creation of the risk tier bins.

## Key DAX Measures

- Default Rate
- Portfolio at Risk
- Recidivism Rate
- Composite Risk Score
- Risk Tier Classification (using COUNTROWS and FILTER)
- Month over Month and Year over Year variance measures

## Tools Used

- Power BI (data modeling, DAX, report design)
- Power Query (data cleaning and transformation)
- DAX (measure development)
- Python (python pptx) for generating executive summary presentations from the dashboard insights

## Repository Structure

```
Nova-Bank-Credit-Risk-Analytics/
├── pbix/
│   └── Credit_Risk_Analysis.pbix
├── data/
│   └── (dataset or data source link)
├── screenshots/
│   └── (dashboard preview images)
└── README.md
```

## Dashboard Preview

Add screenshots of the report pages here once exported from Power BI. Screenshots make the project scannable for recruiters who will not open the pbix file directly.

## Insights

Add two or three headline findings here once finalized, for example the segment with the highest default rate or the country with the largest portfolio at risk. Keeping this section short and specific gives readers the payoff without needing to open the file.

## How to Use

1. Clone this repository
2. Open `pbix/Credit_Risk_Analysis.pbix` in Power BI Desktop
3. Refresh the data connection if prompted

## Author

Agbeyo Ayobami Abiodun
Data and Business Analyst
[LinkedIn](https://linkedin.com/in/agbeyo-ayobami-abiodun-356b34244)
