Meta Ads Performance Analytics Dashboard
Executive Summary

Built an end-to-end marketing analytics dashboard in Power BI to evaluate digital ad campaign performance and optimize advertising spend.

The project transforms raw event-level ad interaction data into executive-level KPIs, enabling performance comparison across campaigns, ads, and user segments.

This dashboard is designed to answer one core question:

Where is marketing money generating real return — and where is it being wasted?

Business Objective

Digital campaigns generate massive volumes of impressions and clicks, but decision-makers care about profitability.

This project focuses on:

Measuring campaign efficiency

Identifying high-ROI ads

Detecting budget leakage

Understanding conversion behavior

Supporting data-driven ad spend optimization

Data Architecture & Modeling

The solution integrates four structured datasets:

campaigns.csv

ads.csv

ad_events.csv

users.csv

A relational data model was designed in Power BI, connecting event-level interaction data to campaign and user dimensions.

Key modeling elements:

Fact table for ad events

Dimension tables for campaigns, ads, and users

Proper relationship cardinality

Cleaned and transformed data before modeling

This ensures accurate aggregation, filtering, and drill-down capability.

KPI Engineering (DAX-Driven Metrics)

Custom DAX measures were created to dynamically calculate:

Total Impressions

Total Clicks

Total Conversions

Click-Through Rate (CTR)

Cost Per Click (CPC)

Conversion Rate

Return on Investment (ROI)

Total Spend

Measures were built using context-aware logic to ensure accuracy under slicers and filters.

This demonstrates practical understanding of DAX beyond basic aggregation.

Dashboard Capabilities

Executive KPI summary view

Campaign-level ROI comparison

Ad-level performance breakdown

Conversion funnel analysis

Interactive slicers for segmentation

Drill-down analysis for deeper insights

The dashboard enables rapid identification of:

Top-performing campaigns

Underperforming ads consuming budget

High-engagement but low-conversion segments

Opportunities for cost optimization

Key Analytical Insights

High CTR does not guarantee strong ROI.

A small subset of ads drives a disproportionate share of conversions.

Budget allocation inefficiencies can be detected through CPC and conversion rate patterns.

Campaign performance varies significantly across user segments.

These findings support strategic reallocation of advertising budgets.

Tools & Technologies

Power BI Desktop

DAX (Data Analysis Expressions)

Relational Data Modeling

CSV Data Integration

Project Value

This project demonstrates:

Business-oriented analytics thinking

Strong data modeling capability

KPI design aligned with real marketing goals

DAX proficiency

Ability to convert raw data into decision-ready insights

Future Enhancements

Time-based trend analysis

Forecasting campaign ROI

Cohort-based user segmentation

A/B testing performance comparison

Publishing to Power BI Service for stakeholder access

How to Run

Download the .pbix file.

Open in Power BI Desktop.

Ensure source CSV files are linked correctly.

Refresh the model if needed.
