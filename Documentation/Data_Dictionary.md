# Data Dictionary

This document describes the fields available in the Amazon sales dataset used for the Power BI analysis.

## Dataset Overview

| Attribute | Details |
|---|---|
| Total Records | 89,082 |
| Time Period | January 2019 – December 2022 |
| Source Format | Excel |
| Worksheet | Amazon_Data |

## Field Definitions

| Column | Description | Data Type |
|---|---|---|
| Product Category | Category assigned to the product | Text |
| Product Description | Description/name of the product | Text |
| Price(Dollar) | Product price in US dollars | Numeric |
| Number of reviews | Number of reviews associated with the product | Numeric |
| Shipment | Shipment/destination information | Text |
| Order Date | Date associated with the order record | Date |

## Data Preparation

The dataset was prepared for analysis in Power BI. Date-related attributes were derived from the `Order Date` field to support time-based analysis, including:

- Year
- Quarter
- Month
- Week

These fields support the dashboard's monthly, weekly, quarterly, and year-to-date analysis.
