# -Salon-Analysis-Dashboard
This project demonstrates how data visualization and business intelligence can support operational planning, service management, and data-driven decision-making in the beauty and wellness industry.
# 🌸 Bed of Roses Spa — Salon Analysis Dashboard

**A Data Analytics Project | Beauty, Spa & Salon Business Intelligence**

## 📌 Project Overview

# &#x20;Salon Analysis Dashboard

The dashboard provides a visual overview of important business indicators, helping stakeholders investigate service demand, changes in client activity over time, and appointment cancellation patterns.

Using an interactive dashboard interface, users can filter information by service, year, month, and other available categories to examine specific areas of business performance.

This project demonstrates how data visualization and business intelligence can support operational planning, service management, and data-driven decision-making in the beauty and wellness industry.

**Project Name:** Bed of Roses Spa — Salon Analysis Dashboard
**Industry:** Beauty, Spa & Salon
**Project Category:** Data Analytics and Business Intelligence
**Dashboard Tool:** Microsoft Excel
**Primary Focus:** Client activity, service pricing, appointment trends, and cancellation analysis
**Project Status:** Dashboard developed; further validation and enhancements are possible.

---

## 🎯 Project Objectives

The main objective of this project is to transform salon-related data into a structured visual report that can help business owners better understand their operations.

Specific objectives include:

- Summarize the number of client records represented in the dataset.
- Analyze the aggregate value of recorded service prices.
- Examine the average number of days represented by the dashboard's time-based metric.
- Explore client activity across different months.
- Compare service prices across salon treatments.
- Investigate appointment cancellation statuses and related patterns.
- Provide interactive filters for exploring different reporting periods and service categories.
- Identify opportunities for improving appointment management and business reporting.
- Demonstrate how data analytics can be applied to a real-world beauty business problem.

---

## 💼 Business Problem

Beauty and spa businesses depend on effective appointment management, customer satisfaction, appropriate service pricing, and efficient use of staff and resources.

However, when business information is stored in spreadsheets or booking records, it can be difficult to identify meaningful trends without additional analysis.

For example, a salon owner may want to understand which services have higher recorded prices, when client activity changes, or which cancellation categories deserve further investigation.

This project addresses these reporting needs by organizing selected business indicators into one dashboard.

The dashboard provides a starting point for exploring client records, service pricing, monthly activity, and cancellation-related categories.

### Key Business Questions

1. How many client records are represented in the dataset?
2. What is the aggregate value of the recorded service prices?
3. What does the average-days KPI measure?
4. How does client activity vary across the displayed months?
5. Which salon services have higher or lower aggregate service prices?
6. How are appointment records distributed across the displayed cancellation statuses?
7. How does client activity change when filtering by year or month?
8. Which services or appointment patterns require further investigation?
9. How could the business use its booking data to improve operational efficiency?
10. What additional information is required to measure revenue, cancellations, and customer retention accurately?

---

## 📊 Key Performance Indicators (KPIs)

The dashboard displays three headline metrics.

| KPI                  | Displayed Value | Purpose                                                                    |
| -------------------- | --------------: | -------------------------------------------------------------------------- |
| Count of Client Code |           1,000 | Summarizes the number of client-code records counted                       |
| Sum of Service Price |          57,895 | Displays the aggregate of service price values                             |
| Average Days         |          61.144 | Displays an average-days measure whose exact definition needs confirmation |

### 1. Count of Client Code

This metric counts client-code records in the underlying data.

It provides an overview of the volume of records represented in the dashboard.

**Important:** A count of client codes does not necessarily equal the number of unique customers. If a customer can appear in multiple booking records, a distinct count of client codes or customer IDs would be required to calculate the unique customer total.

### 2. Sum of Service Price

This metric adds the recorded service price values included in the current reporting context.

It helps summarize the aggregate value of the selected service prices.

**Important:** This metric should not automatically be described as actual revenue. To calculate revenue accurately, the analysis must establish whether the records represent completed and paid services and whether discounts, refunds, and other adjustments are included.

### 3. Average Days

The dashboard displays an average-days value of 61.144.

This metric could help describe a time-related business pattern, but its precise interpretation depends on the field used in the calculation.

Before presenting it as a business finding, confirm whether it measures the interval between appointments, days between booking and cancellation, or another date-related measure.

---

## 📈 Dashboard Features and Visualizations

### 1. Client Activity Trend Analysis

The dashboard includes a line chart showing the count of client-code records across the displayed months.

The chart makes it possible to explore changes in record counts over time and identify periods that may require further investigation.

**Business value:**

- Monitor changes in recorded client activity.
- Identify periods with higher or lower record counts.
- Investigate potential seasonal patterns.
- Support appointment planning and resource allocation.

The underlying date field and chart aggregation should be verified before interpreting the trend as completed appointments, bookings, or cancellations.

### 2. Appointment Cancellation Status Analysis

A doughnut chart displays the distribution of records across cancellation-related categories, including:

- Client canceled
- Client no-show
- Double-booked
- Emergency closure
- Rescheduled
- Service issue
- Staff unavailable

This visualization allows users to compare the counts represented by different appointment statuses.

**Business value:**

- Identify cancellation categories that deserve attention.
- Investigate possible scheduling and communication issues.
- Evaluate the need for appointment reminders.
- Support better planning for staff availability and service delivery.

The displayed categories should be validated against the underlying booking records before calculating cancellation rates or drawing conclusions about the most common cancellation reasons.

### 3. Service Price Analysis

A horizontal bar chart compares the aggregate service price values across salon services.

The visible service categories include:

- Waxing
- Spa Treatment
- Skincare
- Pedicure
- Nail Art
- Massage
- Manicure
- Makeup
- Haircut
- Hair Styling
- Hair Color
- Facial
- Eye Brows
- Body Scrub

**Business value:**

- Compare the aggregate recorded price values by service.
- Investigate services that contribute more to the displayed total.
- Review the relationship between service prices and booking volume.
- Support service pricing and marketing discussions.

**Important:** A chart showing the sum of service prices is not necessarily a chart of the most profitable services. Profitability analysis requires cost information, and a fair price comparison should consider individual prices, booking counts, and service volume.

### 4. Year Filter

The dashboard includes a year-related filter, with 2023 and 2024 visible.

This filter supports the exploration of records across the available reporting years.

**Business value:**

- Compare activity across reporting years.
- Investigate changes in recorded service activity.
- Support annual business reporting.

### 5. Month Filters

The dashboard includes month-based filters, allowing users to select particular months such as January, February, March, and other available periods.

**Business value:**

- Explore month-specific patterns.
- Compare service activity across selected periods.
- Investigate unusual changes in booking or cancellation records.

The screenshot shows February selected in the visible month filters; results will depend on the workbook's actual filter configuration.

### 6. Service Filter

Users can select individual service categories, including Makeup, Manicure, Massage, and Nail Art.

**Business value:**

- Focus the analysis on a specific treatment.
- Compare service-related records.
- Investigate differences in price totals and client activity.

### 7. Staff and Additional Reporting Area

The screenshot also includes a chart area with generic labels such as "Grand Total" and "Axis Title."

This suggests an opportunity to improve the dashboard by adding a clearly defined staff-performance analysis or replacing the incomplete visual with a more useful business metric.

A staff analysis could compare completed appointments, service revenue, booking volume, or customer ratings by staff member if the necessary data is available.

---

## 🔍 Initial Observations

The following observations are based on the uploaded dashboard screenshot. They should be verified against the source workbook before being treated as formal findings.

### Overall Record Volume

The dashboard displays a count of 1,000 client-code records.

This indicates that the current dashboard summarizes 1,000 counted records, although the number of unique customers still needs to be confirmed.

### Aggregate Service Price

The displayed sum of service prices is 57,895.

The currency and the meaning of this aggregation should be confirmed before interpreting it as total sales or revenue.

### Time-Based Activity

The line chart shows variation in record counts across the displayed months, including a noticeable decline toward the end of the displayed period.

This pattern warrants further investigation. Possible explanations could include incomplete reporting periods, changes in booking activity, cancellations, or data-quality issues. The chart alone does not establish the cause.

### Differences Across Services

The service-price chart shows variation in aggregate values among the listed salon treatments.

Further analysis of service prices, booking frequency, service costs, and completed appointments would help determine which services contribute most meaningfully to the business.

### Cancellation-Related Categories

The doughnut chart presents several cancellation-related statuses. Comparing their counts could help identify areas for additional investigation into booking reliability and appointment management.

Actual cancellation rates require a suitable denominator, such as total booked appointments, and a clearly defined cancellation-status field.

---

## 💡 Business Recommendations

The following recommendations are potential actions to investigate using the underlying data.

### 1. Improve Appointment Management

Review cancellation and no-show records to determine whether appointment reminders, clearer booking policies, or confirmation procedures could reduce avoidable missed appointments.

### 2. Monitor Service Performance

Compare each service using booking volume, individual service price, completed appointments, and revenue to understand demand more accurately.

### 3. Investigate Monthly Trends

Examine changes in client activity across months and reporting years. Check whether the patterns are consistent and whether incomplete periods or missing records affect the results.

### 4. Strengthen Customer Retention Analysis

If customer identifiers and appointment dates are available, calculate repeat booking rates, visit frequency, and customer retention over defined periods.

### 5. Improve Revenue Reporting

Separate completed and paid appointments from canceled, rescheduled, or unpaid bookings. Account for discounts and refunds where applicable before calculating revenue.

### 6. Evaluate Service Profitability

Include service delivery costs, staff costs, and other relevant expenses to identify services that contribute the greatest profit rather than simply having higher aggregate prices.

### 7. Improve Staff and Scheduling Reports

If staff identifiers and appointment outcomes are available, create a dedicated staff-performance view showing completed appointments, booking volume, and service revenue.

### 8. Standardize Business KPIs

Document the formula, source field, time period, and business meaning of each KPI so that the dashboard provides consistent information.

---

## 🛠️ Tools and Technologies

### Microsoft Excel

Microsoft Excel is the apparent dashboarding tool based on the uploaded screenshot.

Relevant Excel features may include:

- PivotTables for aggregating client and service records.
- PivotCharts for visualizing trends and comparisons.
- Slicers for interactive filtering.
- Date filters for year and month analysis.
- Dashboard layout and KPI cards.
- Spreadsheet formulas and data preparation.

The specific features used should be confirmed from the workbook.

### Potential Future Tools

**SQL:** Could be used to query appointment records, group results by service, calculate booking counts, and investigate cancellation patterns.

**Power BI:** Could be used to build an enhanced dashboard with a formal data model, DAX measures, drill-through reports, and additional interactive visuals.

These tools should be listed as project technologies only after they have actually been used in the project.

---

## 📁 Recommended GitHub Repository Structure

```text
bed-of-roses-spa-analysis/
│
├── README.md
│
├── dashboard/
│   └── salon_analysis_dashboard.png
│
├── data/
│   └── README.md
│
├── analysis/
│   └── methodology.md
│
├── reports/
│   └── salon_analysis_report.pdf
│
└── LICENSE
```

### File Descriptions

- `README.md`: Project overview, business problem, dashboard features, findings, and recommendations.
- `dashboard/`: Screenshot or exported image of the dashboard.
- `data/`: Dataset or instructions for accessing the data, where permitted.
- `analysis/`: KPI definitions, analysis methodology, and data-quality notes.
- `reports/`: Optional written report summarizing the analysis.
- `LICENSE`: Optional license describing reuse permissions for your original work.

Only upload files that exist. You can add the analysis notes and report later if you have not created them yet.

Do not upload private customer records or confidential business information. If the data is sensitive, publish an appropriately anonymized or synthetic dataset instead.

---

## 🚀 How to Use the Dashboard

1. Open the Excel workbook containing the dashboard.
2. Review the headline KPIs.
3. Select a year to explore the relevant reporting period.
4. Use the month filters to focus on a particular month.
5. Select a service to examine service-related results.
6. Review the line chart for changes in the displayed record counts.
7. Explore the doughnut chart to compare cancellation-related categories.
8. Review the service-price chart to compare aggregate values.
9. Record observations and validate them against the source data before making recommendations.

**Note:** The screenshot is a static preview. The original Excel workbook is needed to interact with the dashboard filters and inspect the calculations.

---

## 🚧 Limitations and Future Improvements

Potential improvements include:

- Add a unique customer count alongside the total record count.
- Calculate confirmed revenue from completed and paid appointments.
- Add a clearly defined cancellation rate.
- Separate cancellations, no-shows, rescheduled appointments, and completed bookings.
- Add booking volume by service.
- Introduce service profitability analysis.
- Add a customer retention and repeat-visit analysis.
- Improve the incomplete staff chart.
- Remove generic axis labels and unnecessary chart legends.
- Standardize currency and number formats.
- Document all KPI definitions.
- Validate date fields and investigate missing or unusual values.
- Rebuild the dashboard in Power BI as an extension of the project.

These enhancements would improve the accuracy, usability, and business value of the dashboard.

---

## 👩‍💻 About the Analyst

I am a Data Analyst with an interest in business intelligence, data visualization, and using data to solve real-world business problems. My technical interests include Microsoft Excel, Power BI, and SQL.

As a beauty business owner, I am particularly interested in applying data analytics to customer behavior, service demand, appointment management, and business performance in the beauty and wellness industry.

This project reflects my interest in combining analytical thinking with practical business understanding to develop useful, data-driven recommendations.

### Connect With Me

- **GitHub:** [https://github.com/Analyst-KITAN12](https://github.com/Analyst-KITAN12)
- **LinkedIn:** [https://www.linkedin.com/in/olayiwola-sukurat-olaitan-195502433](https://www.linkedin.com/in/olayiwola-sukurat-olaitan-195502433)
- **Email:** [kkitan30@gmail.com](mailto\:kkitan30@gmail.com)
- **Instagram:** [https://www.instagram.com/\_\_kkitan__12/](https://www.instagram.com/__kkitan__12/)

---

## 📝 Conclusion

The Bed of Roses Spa Salon Analysis Dashboard demonstrates how salon-related data can be transformed into a visual reporting tool for exploring client activity, service price totals, appointment timing, and cancellation-related categories.

The project provides a foundation for improving appointment management, evaluating service performance, and developing more detailed customer and revenue analytics.

With further data validation and additional measures, the dashboard can become a more comprehensive business intelligence resource for a beauty and spa business.

**Thank you for visiting this project!**

Feel free to explore my GitHub portfolio and connect with me on LinkedIn.
