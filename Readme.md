# Cable Tech Company | Customer, Recharge & Viewing Analytics

A Power BI analytics project developed during my internship at **Cable Tech Company**. The project turns cable-television customer, recharge, and channel-preference data into an interactive dashboard to support operational and customer-focused decisions.

## Project Overview

Cable operators manage customer connections, recurring recharges, package selections, payment status, and viewing preferences. When this information is spread across multiple records, it can be difficult to identify customer trends, monitor recharge activity, and understand what viewers prefer.

I developed this project to bring these areas together in a single reporting experience. The dashboard helps explore the customer base, track recharge patterns, compare package and payment activity, and understand channel preferences.

## Business Questions

The analysis is designed to help answer questions such as:

- How many customers are in the customer base, and how are they distributed across areas?
- Which subscription packages are most commonly selected?
- How does recharge activity change month by month and year by year?
- What is the status of customer payments, and which payment methods are used?
- Which channel categories and individual channels are preferred by viewers?
- How do customer activity and viewing preferences vary across customer groups?
- Which areas or customer segments may need closer operational attention?

## Dashboard Highlights

The Power BI report includes interactive KPI cards, charts, and filters to explore key areas of the business, including:

- **Customer overview:** customer and connection distribution.
- **Recharge analysis:** recharge trends over time and transaction activity.
- **Package analysis:** comparison of package selections and recharge amounts.
- **Payment analysis:** paid/pending status and payment-method breakdown.
- **Channel preferences:** popular channel categories and channels.
- **Customer segmentation:** comparisons by area and customer group.

Use the report filters and slicers to explore the data from different perspectives.

## Dataset: Cable Tech Company

The accompanying Excel workbook is organised into three main data tables:

| Table | Description |
|---|---|
| `Customers_1000` | Customer-level information, including customer ID, area, recharge date, package, operator, payment details, connection status, and viewing hours. |
| `Recharge_Transactions` | Recharge-level records, including transaction ID, customer ID, recharge date, amount, package, payment status, and payment method. |
| `Channel_Preferences` | Customer channel preferences, including channel category, channel name, preference rank, and estimated monthly viewing hours. |

### Dataset at a glance

- **1,000** customer records.
- **3,541** recharge transaction records.
- **2,511** channel-preference records.
- Separate customer ID, customer name, and area fields.
- Date fields available for monthly and yearly trend analysis.
- Package, payment, connection, operator, and viewing-related attributes.

> **Data note:** The workbook is a practice/analysis dataset containing a combination of reference records and synthetic records. It should not be interpreted as a complete export of the company's live customer or transaction system. Any conclusions are limited to the data provided in the workbook.

## Tools & Technologies

- **Microsoft Excel** — reviewing and understanding the source data.
- **Power Query** — data preparation, cleaning, and transformation.
- **Power BI** — data modelling, measures, interactive visuals, and dashboard development.
- **DAX** — calculations and analytical measures.

## Data Preparation & Modelling

The workflow focused on making the source data suitable for analysis:

1. Reviewed the workbook structure and checked the available fields.
2. Examined customer, recharge, and channel-preference records separately.
3. Used customer and transaction identifiers to support analysis across the tables.
4. Checked date, amount, package, payment, and category fields for consistent reporting.
5. Prepared date-related fields for monthly and yearly trend analysis.
6. Built the report visuals and interactive filtering experience in Power BI.

The customer ID is the key field for connecting customer-level information with related recharge and preference records. The transaction table contains multiple records per customer, so it should be analysed at transaction level when measuring recharge activity.

## Skills Demonstrated

- Data understanding and preparation
- Excel and Power Query
- Power BI report development
- Data modelling and relationships
- DAX measures and KPI reporting
- Time-based trend analysis
- Customer and transaction analysis
- Translating business questions into visual insights

## Project Files

| File | Description |
|---|---|
| `Cable Tech Company.pbix` | Power BI report file. |
| `Cable Tech Company.xlsx` | Excel dataset used for the analysis. |
| `README.md` | Project documentation. |

*The filenames above are suggested repository names. Rename the files accordingly when uploading them to GitHub.*

## How to Explore the Project

1. Download or clone this repository.
2. Open `Cable Tech Company.xlsx` to review the source tables.
3. Open `Cable Tech Company.pbix` in Microsoft Power BI Desktop.
4. Use the report pages, slicers, and filters to explore customer, recharge, package, payment, and channel-preference trends.

## Internship Context

This project was completed as part of my internship at **Delocala Cable Tech Company**. It provided practical experience in working with structured business data, preparing datasets for reporting, building Power BI visuals, and presenting information in a way that supports business understanding.

## Conclusion

The **Cable Tech Company** project demonstrates how customer, recharge, and viewing-preference data can be organised into a clear analytical report. It showcases my ability to work through a data-analysis workflow—from understanding the dataset and preparing it for reporting to building an interactive Power BI dashboard around practical business questions.

---

**Author:** syed khaja faqruddin
**LinkedIn: linkedin.com/in/syed-khaja-faqruddin-9b67b2380  
**GitHub: github.com/syedkhajafaqruddin
**Project:** Cable Tech Company  
**Tools:** Excel | Power Query | Power BI | DAX
