# Retail Risk Intelligence Center

## Project Overview

The **Retail Risk Intelligence Center** is an end-to-end Business Intelligence and Risk Analytics solution developed using the Microsoft Extended Contoso Retail Dataset. The project was designed to move beyond traditional descriptive reporting by identifying and monitoring operational and financial risks that may impact future business performance.

The solution integrates data across multiple business functions, including sales, inventory management, customer satisfaction, and order fulfilment, to provide a unified view of organisational risk exposure.

---

## Business Problem

Retail organisations often focus on historical performance reporting but lack visibility into emerging risks that may affect future performance.

### Business Question

**What risks could prevent Contoso from achieving its operational and financial objectives?**

---

## Project Objectives

* Monitor revenue performance and target attainment.
* Identify inventory-related operational risks.
* Assess customer satisfaction and customer risk.
* Evaluate fulfilment performance and service-level compliance.
* Develop a unified Overall Risk Score.
* Support proactive and data-driven decision-making.

---

## Solution Architecture

```text
Parquet Files
      ↓
Python Data Preparation
      ↓
Azure SQL Database
      ↓
SQL Data Validation
      ↓
Power BI Data Model
      ↓
DAX KPI Framework
      ↓
Retail Risk Intelligence Center Dashboard
      ↓
Power BI Service Deployment
      ↓
Business Users & Decision Makers
```

---

## Technologies Used

### Data Preparation

* Python
* Pandas

### Database

* Azure SQL Database
* SQL Server

### Data Validation

* SQL

### Business Intelligence

* Power BI
* DAX

### Data Modelling

* Constellation Schema
* Dimensional Modelling

---

## Data Validation Activities

The dataset was validated before modelling and dashboard development.

Validation activities included:

* Dataset completeness validation
* Currency consistency validation
* Product dimension validation
* Inventory structure validation
* Customer survey coverage assessment
* Relationship validation
* Data quality assessment

---

## Data Model

A constellation schema architecture was implemented using multiple fact tables connected to shared business dimensions.

### Fact Tables

* StoreSales
* OnlineSales
* Inventory
* SalesQuota
* CustomerSurvey
* OrderFulfillment

### Dimension Tables

* Date
* Product
* Store
* Customer

---

## Risk Framework

The dashboard evaluates four core business risk domains.

### Revenue Risk

Measures the likelihood of failing to achieve revenue targets.

### Inventory Risk

Measures inventory exposure resulting from stock imbalances, overstocking, low stock, and stock-outs.

### Customer Risk

Measures customer dissatisfaction based on customer survey responses.

### Fulfilment Risk

Measures delivery failures and service-level agreement breaches.

### Overall Risk Score

```text
Overall Risk Score =
(Revenue Risk × 25%)
+ (Inventory Risk × 25%)
+ (Customer Risk × 25%)
+ (Fulfilment Risk × 25%)
```

---

## Dashboard Pages

### Executive Risk Overview

Provides a consolidated view of overall organisational risk exposure and key business risk indicators.

### Revenue Risk Center

Monitors sales performance, quota attainment, revenue gaps, and revenue risk drivers.

### Inventory Risk Center

Identifies inventory exposure, stock health issues, inventory concentration risks, and inventory root causes.

### Customer & Service Risk Center

Evaluates customer satisfaction, Net Promoter Score (NPS), fulfilment performance, and SLA compliance.

### Project Documentation & Methodology

Documents the project architecture, methodology, validation findings, KPI framework, and implementation approach.

---

## Key Findings

| Risk Area       | Risk Score |
| --------------- | ---------- |
| Overall Risk    | 53.38%     |
| Inventory Risk  | 79.61%     |
| Revenue Risk    | 57.97%     |
| Fulfilment Risk | 47.33%     |
| Customer Risk   | 28.63%     |

### Key Insight

Inventory Risk was identified as the most significant contributor to overall business risk, indicating substantial inventory exposure across multiple stock conditions.

---

## Live Dashboard

🔗 **[Retail Risk Intelligence Center Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiMDI3NWJlMDktOGUxZC00MGMxLWJlYjUtMGRhNDM4ODZiNjlkIiwidCI6IjI0OWVhMzg4LWIzMzMtNDk5NS05YWVmLTIxZmExNGRhNmJlYiJ9)**

Explore the interactive dashboard to analyze:

* Revenue Risk
* Inventory Risk
* Customer Risk
* Fulfilment Risk
* Overall Business Risk
* Root Cause Analysis
* Executive Decision Support

---

## Project Documentation

📄 **[Retail Risk Intelligence Center Project Report](https://github.com/sh184roman/Retail-Risk-Intelligence-Center/blob/main/Retail_Risk_Intelligence_Center_Report.pdf)**

The report includes:

* Business Understanding
* Data Collection & Architecture
* Data Validation & Quality Assessment
* Data Modelling
* KPI Framework & Risk Methodology
* Dashboard Development
* Key Findings & Recommendations
* Assumptions & Limitations
* Technical Implementation Details

---

## Technical Skills Demonstrated

* Python
* SQL
* Azure SQL Database
* Data Validation
* Data Modelling
* Power BI
* DAX
* Business Intelligence
* Dashboard Design
* Data Storytelling
* Risk Analytics
* Business Analysis

---

## Author

**Roman Shrestha**

*MSc International Business with Data Analytics*

**Data Analyst | Power BI Developer | SQL | Python | Data Visualisation**
