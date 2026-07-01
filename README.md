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

## Dashboard Preview

<img width="918" height="512" alt="Screenshot 2026-07-01 125336" src="https://github.com/user-attachments/assets/7f3279bc-2778-4abc-af8f-e08c0d63931b" />

<img width="915" height="510" alt="Screenshot 2026-07-01 125516" src="https://github.com/user-attachments/assets/6f24d17b-380d-4dae-a1c6-3fe5ff5ab982" />

<img width="920" height="512" alt="Screenshot 2026-07-01 125551" src="https://github.com/user-attachments/assets/d71db044-74f2-47de-a5ff-154d1ab74554" />

<img width="922" height="510" alt="Screenshot 2026-07-01 125647" src="https://github.com/user-attachments/assets/41c9aa67-14fd-4556-8a49-4a1c84ffa0a1" />

## Insights
<img width="839" height="472" alt="Screenshot 2026-07-01 130208" src="https://github.com/user-attachments/assets/c6fe2e9e-817e-415c-9d57-0c83a09884a4" />

## Recommendation
<img width="838" height="472" alt="Screenshot 2026-07-01 130256" src="https://github.com/user-attachments/assets/d8db2514-42a2-4cc2-982c-6e01575eb38e" />


## Author
Agbeyo Ayobami Abiodun
Data and Business Analyst
[LinkedIn](https://linkedin.com/in/agbeyo-ayobami-abiodun-356b34244)
