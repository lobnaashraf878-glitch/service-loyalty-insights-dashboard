Service Loyalty & Revenue Insights Dashboard

An interactive Power BI dashboard for analyzing service revenue, customer loyalty, repeat bookings, satisfaction, customer behavior, and channel performance.

Repository Name

service-loyalty-insights-dashboard

Repository Description


Interactive Power BI dashboard for analyzing service revenue, customer loyalty, repeat bookings, satisfaction scores, customer behavior, and channel performance.

Overview

This project provides a multi-page analytical view of service-business performance and customer loyalty. It helps teams understand which services generate the most revenue, which channels perform best, how customers behave after their first booking, and how satisfaction relates to spending and repeat activity.

The dashboard is built in Microsoft Power BI and uses a service and customer insights dataset modeled in the Service_Loyalty_Insights table.

Report Pages

1. Overview

The overview page summarizes the main business and customer metrics:

•
Total revenue

•
Repeat customers

•
Repeat rate percentage

•
Average customer score

•
Revenue trend over time

•
Revenue by revenue type

•
Revenue by channel

2. Service Analysis

This page focuses on service-level performance and customer loyalty:

•
Repeat customers by service type

•
Average customer score by repeat-booking behavior

•
Repeat rate by service

•
Customer-level spending and average score

•
Total customers

•
Most loyal service

•
Loyal customer percentage

•
Satisfaction gap

3. Revenue & Customer Insights

This page explores the relationship between services, revenue, spending, satisfaction, and customer behavior:

•
Revenue by service type

•
Spending by repeat-booking behavior

•
Customer count by customer score

•
Relationship between customer score and total revenue

•
Customer distribution by service type

Key KPIs

KPI
Description
Total Revenue
Total revenue generated within the selected filters
Repeat Customers
Number of customers who made repeat bookings
Repeat Rate %
Percentage of customers or bookings classified as repeat activity
Average Customer Score
Average satisfaction or customer experience score
Total Customers
Number of customers in the selected context
Most Loyal Service
Service type with the strongest repeat-customer performance
Loyal Customer Percentage
Percentage of customers classified as loyal
Satisfaction Gap
Difference between relevant satisfaction or customer-score groups
Total Spend
Total customer spending used for customer-level analysis




Main Analyses

Service Performance

Compare service types based on revenue, repeat customers, and repeat-booking behavior to identify the services that create the strongest customer retention.

Customer Loyalty

Analyze repeat bookings, repeat rates, loyal customer percentage, and customer spending to understand retention and loyalty patterns.

Customer Satisfaction

Use customer scores and average scores to evaluate service quality and identify gaps between satisfaction and repeat behavior.

Channel Performance

Compare revenue generated through different channels and evaluate how channel choice contributes to overall business performance.

Revenue and Customer Behavior

Explore how customer score, service type, repeat behavior, and total revenue relate to each other through bar charts, column charts, and scatter analysis.

Report Filters

The dashboard includes interactive slicers for:

•
Real Date — filter the analysis by date

•
Channel — compare performance across acquisition or service channels

•
Service Type — focus on a specific service category

The filters are available across the report pages to support consistent analysis.

Data Model

The report is primarily built around the following table:

•
Service_Loyalty_Insights — contains service, customer, revenue, loyalty, booking, channel, date, spending, and satisfaction fields

The report uses measures and analytical fields such as:

•
Total Revenue

•
Repeat Customers

•
Repeat Rate %

•
Avg Customer Score

•
Total Customers

•
Most Loyal Service

•
Loyal Customer Percentage

•
Satisfaction Gap

•
Total Spend

Tools and Technologies

•
Microsoft Power BI Desktop

•
Power Query

•
DAX

•
Interactive data visualization

•
Customer loyalty analysis

•
Service and revenue performance analysis

Getting Started

1.
Download or clone this repository.

2.
Open the .pbix file using Power BI Desktop.

3.
Review the data source and update credentials or file paths if required.

4.
Refresh the data model.

5.
Navigate between the Overview, Service Analysis, and Revenue & Customer Insights pages.

6.
Use the slicers to explore results by date, channel, and service type.

Bash


git clone https://github.com/<your-username>/service-loyalty-insights-dashboard.git



Suggested Repository Structure

Plain Text


service-loyalty-insights-dashboard/
├── README.md
├── servicesanalysis.pbix
├── assets/
│   └── dashboard-preview.png
└── docs/
    └── data-dictionary.md



Business Questions Answered

•
Which services generate the highest revenue?

•
Which services have the most repeat customers?

•
What is the repeat rate for each service type?

•
Which service is the most loyal from a customer-retention perspective?

•
What percentage of customers can be classified as loyal?

•
How does customer satisfaction vary by repeat-booking behavior?

•
Which channels generate the most revenue?

•
How much do repeat customers spend compared with non-repeat customers?

•
Is higher customer satisfaction associated with higher revenue?

•
Where is the gap between customer satisfaction and loyalty performance?

Recommended Uses

•
Service portfolio reviews

•
Customer retention analysis

•
Loyalty and repeat-booking monitoring

•
Customer experience reporting

•
Channel performance reviews

•
Revenue and service strategy planning

Notes

•
KPI values update dynamically according to the selected filters.

•
Validate the business definitions of repeat customers, loyal customers, repeat rate, and satisfaction gap before using the dashboard for official reporting.

•
Review data refresh settings and source credentials before publishing to Power BI Service.

•
Do not commit confidential or personally identifiable customer information to a public repository.

License

Add the license that matches your organization or project requirements. For internal customer analytics, consider using a private repository and documenting the approved data-access policy.

