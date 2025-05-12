GhanaPay Analytics Project 📊
Overview
This project analyzes transaction data for GhanaPay, a digital financial service, to extract insights on customer behavior, identify growth opportunities, and recommend improvements to enhance customer experience. It combines data preparation in Excel with advanced data modeling and dashboarding in Power BI.

🔍 Objective
To analyze sample transaction data from GhanaPay to:

Identify trends in mobile money, digital payments, and micro-lending.

Detect transaction anomalies and service gaps.

Improve decision-making using visualized insights.

📁 Repository Contents
File	Description
GhanaPay - Data Set 2.xlsx	Raw and cleaned transaction data with new feature engineering.
GhanaPay_Final.pbix	Power BI report containing visual dashboards and KPIs.
GHANA PAY PROJECT.docx	Project summary, analysis insights, methodology, and recommendations.

🧹 Data Cleaning & Feature Engineering
Performed in Excel:

Removed duplicates and checked for missing values.

Added Category column via VLOOKUP to classify transactions (Mobile Money, Digital Payment, Micro-lending).

Converted transaction Amount to 2 decimal places and added currency.

Split Timestamp into Date and Time.

Derived a new Time of Day column to classify transaction timing (Morning, Afternoon, Evening).

Created Channel column to group device types (Mobile App vs. USSD) using VLOOKUP.

📊 Power BI Dashboard
Key dashboards and visual elements include:

Transaction Overview: Monthly transaction volume and value trends.

Channel Usage: Comparison between Mobile App and USSD performance.

Service Category Analysis: Breakdown by Mobile Money, Digital Payments, and Micro-lending.

Time of Day Analysis: User activity trends and failure rates by time of day.

Regional Insights: Performance tracking with focus on Accra.

🔎 Key Insights
8% Transaction Failure Rate: Needs attention to improve trust and reduce churn.

Underperformance in Accra: Potential for strategic expansion or targeted campaigns.

Usage Peak in March: Sharp drop in April (-95.4%) calls for user re-engagement.

Time-Based Trends: Mornings had the highest number and failure rate of transactions.

Mobile App Dominance: 73% of transaction value generated via mobile app vs. USSD (27%).

Service Focus: Digital Payments and Micro-lending account for 80% of all volume.

💡 Recommendations
Re-engagement Campaigns: Target inactive users in April with SMS/email nudges or loyalty rewards.

Accra-Focused Strategies: Run localized campaigns and analyze competition or infrastructure issues.

App Enhancements: Prioritize UX/UI improvements and platform stability.

Monitor Key Metrics:

Number of transactions

Average transaction size

Transaction success/failure rate

Channel-specific performance

🧰 Tools Used
Excel: Data cleaning, transformation, and feature engineering.

Power BI: Dashboard development and insights visualization.

🚀 Getting Started
Download or clone this repo.

Open GhanaPay - Data Set 2.xlsx to explore cleaned and engineered data.

Open GhanaPay_Final.pbix in Power BI Desktop to view dashboards and run further analysis.

📌 Conclusion
This project provides valuable insights into GhanaPay’s operational trends and user behavior. Addressing high failure rates, enhancing mobile app reliability, and re-engaging inactive users can significantly drive business growth.

🌐 Connect With Me
LinkedIn: https://www.linkedin.com/in/kenneth-hayford/

Twitter:(https://x.com/Mr_hayf0rd)

Portfolio: https://kenneth-hayford.zarlasites.com/
