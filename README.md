# PowerBI-Portfolio
This repository features a curated collection of Power BI dashboards and analytics projects that reflect my proficiency in transforming data into actionable insights through visualizations and storytelling.

## About Me
I’m a data enthusiast with hands-on experience in Power BI, dedicated to turning raw data into meaningful stories through analytics and visualization. This portfolio features a collection of my Power BI projects that demonstrate my ability to design insightful dashboards and empower data-driven decision-making.

## Support system Dashboard
### Objective:

To analyze category-wise support ticket performance, monitor unnecessary reassignment of tickets, measure average resolution time, and identify top and bottom issue categories to improve operational efficiency.

https://github.com/user-attachments/assets/50fcffff-1e4b-4143-b6dc-aa546dc1f7b1

The dashboard focuses on first-time resolution quality, ensuring that raised tickets should resolved or rejected directly without reassignment.

📊 Key Metrics

🔹 _CATEGORY WISE RAISED TICKETS_: Shows the volume of tickets raised per category (Quality, Progress, Drawing, Contract, etc.).

🔹 _REASSIGNED TICKETS_: Tracks how many tickets were reassigned after being raised. 

🔴 _RED FLAG_:  "In the ideal process: A ticket should be resolved or rejected directly without reassigned".
    
🔹 Reassignment indicates misrouting, unclear and poor triaging.

🔹 _AVERAGE RESOLUTION TIME BY CATEGORY_: Measures the average time taken to close a ticket per category.

🔹 _FIRST ATTEMPT CLOSED TICKETS (KPI)_: Indicates how many tickets were closed without reassignment or reopening. Serves as a quality-of-resolution metric.

🎯 Business Insights

🔹 Improves first-time resolution rate.

🔹 Reduces unnecessary ticket reassignment.

🔹 Identifies root causes of recurring issues.


## DailyLogs Dashboard

### Objective:
To monitor daily work package (WP) completion performance by tracking the number of logs completed per day and evaluating whether each work package is completed within, below, or above the defined SLA time range (Min–Max duration).

https://github.com/user-attachments/assets/5af52f0c-392f-4d68-9fef-85796d141be7

📊 Key Metrics

_KPI Cards_

🔴 % Out of Range

For example- ~89.18% indicates a very high share of daily logs are outside the defined Min–Max duration.
This means most work packages are not completed within the acceptable time window.

🔴 Outside Range

For exmple- ~6,646 indicates these work packages were completed either below Min or above Max, both treated as issues.

✅ Within Range

For exmple- ~724 Only a small portion of work packages were completed correctly within Min–Max limits.

🔹 _DAILYLOGS_: Day-wise count of daily logs for the selected Project , Year , Month.

🔹 _ACTUAL DURATION VS MIN & MAX TIME_: Each bar represents a work package’s actual completion duration.

Compared against defined Min and Max thresholds.

✅ Within Min–Max → Correct execution,

🔴 Below Min → Too fast (possible incomplete work / incorrect logging)

🔴 Above Max → Delayed execution

🎯 Business Insight:

🔹 Most work packages fall outside the Min–Max band.

🔹 High log count does not automatically mean good performance — quality depends on Min–Max compliance

🔹 Poor planning or supervision.

🔹 Possible data quality issues.

## Purchase Order Advance

### Objective:

To track purchase order advances paid to vendors, monitor advance recovery through material receipts, and identify pending quantities and financial exposure at material, vendor, and PO levels.
and to verify that vendors supply the correct quantity and quality as committed in the Purchase Order (PO).

https://github.com/user-attachments/assets/e042773d-b0dd-4b18-a659-5f2b54be8cbb

This dashboard enables procurement and finance teams to:

🔹 Monitor advance amount outstanding with vendors

🔹 Track material quantities yet to be received

🔹 Analyze received vs pending quantities by vendor and material

🔹 Identify high-risk POs with low recovery and high balance exposure

📊 Key Metrics

🔹 _RECOVERY AMOUNT AND PENDING AMOUNT_: Displays total pending advance amount currently lying with vendors.

Example Insight: ~90.76% of the advance is recovered, while ~9.24% remains pending — highlighting controlled but active exposure.

🔹 _QUANTITY YET TO BE DELIVERED_: Shows remaining quantity against each PO and material.

Advance is paid where delivery has not started or is delayed

🔹 _VENDOR WISE PERFORMANCE_: Advance recovery %, Delivery completion by vendor

Helps procurement teams prioritize follow-ups with slow-performing vendors.

🎯 Business Insights

🔹 Ensures on-time material availability.

🔹 Early advance payments improve vendor responsiveness and priority execution.

## % of Unassigned Locations

<img width="1319" height="731" alt="image" src="https://github.com/user-attachments/assets/e8e0b570-c75d-4aff-9c83-785ba34890f3" />

## Global vs Local Checkpoints Dashboard

https://github.com/user-attachments/assets/c9ab6dd3-d502-404d-a4ef-7633bdf0f2fa

## Daily Labour Count

### Objective:

To analyze day-to-day usage trends of construction methodologies, to measure user adoption and engagement of the Methodology feature and identify usage patterns.

To monitor manpower utilization,cCorrelate labor strength with productivity and progress and to support cost control and planning decisions.

https://github.com/user-attachments/assets/6445e346-591c-4977-8e6e-9c6dc7692ec8

This dashboard helps project teams understand:

🔹 How methodology adoption changes over time

🔹 How labor strength varies by day, month, and project

📊 Key Metrics

🔹 The line chart shows the usage of methodologies per day

🔹 Daily Labor count capture the actual number of labor deployed on site each day.

🔹 Bar Chart – Daily / Monthly Labor Trend: The bar chart displays labor count over time (daily, monthly, or yearly aggregation).

Each bar represents the total labor deployed for the selected period.

🔹 _PIE CHART_ LABOR DISTRIBUTION_: The pie chart shows labor distribution across projects for the selected time period.

🎯 Business Insights

🔹 Consistent upward trend → Feature is gaining acceptance and trust

🔹 Sharp drops on specific days → Possible usability issues, access problems, or low awareness

🔹Flat or low usage → Feature exists but is not embedded in business process, required training sessions, audits, reviews, or process enforcement

🔹 Enables monthly and yearly labor visibility

🔹 Supports manpower planning and budgeting

🔹 Improves workforce utilization efficiency

## Planned Vs Acheived %

### Objective:
To track cumulative project progress (%) against the planned baseline over time and to evaluate whether the project is achieving the required daily progress rate to meet planned milestones.

https://github.com/user-attachments/assets/fb9ec651-67a3-4cff-88c7-6eb98c5fdb4c

This dashboard helps stakeholders:

🔹 Compare actual achieved progress vs planned progress

🔹 Measure daily required progress (%) vs actual daily achieved (%)

🔹 Support timely corrective actions to ensure on-time project delivery

📊 Key Metrics 

🔹 _TOTAL ACHIEVED%(KPI)_: Represents the cumulative actual progress completed till date.

Example shown: 53.49% achieved against the total project scope.

🔹 _PLANNED VS ACHIEVED TRENDS_: The line chart indicates the target and achieve percentage per day, month, year.
(The shaded area between the curves indicates the progress gap.)

🔹 If Achieved < Planned → Project is behind schedule

   If Achieved ≈ Planned → Project is on track

   If Achieved > Planned → Project is ahead of schedule






