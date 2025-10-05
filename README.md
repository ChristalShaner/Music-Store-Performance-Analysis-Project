# Music-Store-Performance-Analysis-Project

![Overview Dashboard](./images/dashboard)

Overview

This project simulates a fictional Music Store dataset and builds an interactive Power BI report to analyze sales performance. The dataset follows a star schema design and enables drilldown into sales trends, product performance, and customer insights.

Dataset Design

The dataset contains 2,000 rows spanning 3 years and includes:

Fact Table: SalesFact – sales transactions (with quantity, sales, profit).
Dimensions:
DateDim – date hierarchy (Year, Quarter, Month, Day).
ProductDim – product details (Category: Instruments, SheetMusic, Equipment).
CustomerDim – customer details (Segment: Retail, Online, Schools, Professionals, etc.).

Power BI Report Structur
Page 1 – Overview Dashboard
Page 2 – Product Drilldown (Win)
Insight: Instruments show strong YoY growth → company win
Page 3 – Customer Drilldown (Opportunity)
Insight: Low attach rates for accessories → growth opportunity

Key Insights
Win: Instrument sales have grown steadily, driving revenue gains.
Opportunity: Customers often skip accessories (equipment), especially certain segments, leaving upsell potential.

Repository Structure
data
DateDim.csv
ProductDim.csv
CustomerDim.csv
SalesFact.csv

report
MusicStore.pbix

README.md

Author - Christal Shaner
Created as a demo BI project to showcase data modeling, DAX, and business storytelling in Power BI.
