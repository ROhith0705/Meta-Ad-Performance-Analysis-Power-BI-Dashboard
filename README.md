# Meta-Ad-Performance-Analysis-Power-BI-Dashboard

**📄 Project Overview**
This project analyzes advertising performance across Facebook and Instagram campaigns using Power BI. It provides a 360° view of ad effectiveness, from impressions to purchases, to help optimize marketing strategy and ROI.
The dashboard offers insights into audience demographics, engagement behavior, geographic distribution, and time-based trends to identify what drives higher conversions.

**🎯 Business Objective**
To help the marketing team:

Track and compare campaign performance across Facebook and Instagram.
Identify high-performing ad types and target demographics.
Measure budget utilization, conversion efficiency, and audience engagement.
Optimize ad scheduling and spend allocation for maximum ROI.

**📊 Key Performance Indicators (KPIs)**
| KPI                          | Definition                               | Formula                               | Use                         |
| ---------------------------- | ---------------------------------------- | ------------------------------------- | --------------------------- |
| **Impressions**              | Number of times ads were displayed       | Count of event_type = Impression      | Measure reach               |
| **Clicks**                   | Number of times ads were clicked         | Count of event_type = Click           | Engagement intent           |
| **Shares / Comments**        | User interaction metrics                 | Count of event_type = Share / Comment | Viral engagement & feedback |
| **Purchases**                | Number of successful conversions         | Count of event_type = Purchase        | Conversion tracking         |
| **CTR (Click-Through Rate)** | % of impressions resulting in clicks     | (Clicks ÷ Impressions) × 100          | Ad effectiveness            |
| **Engagement Rate**          | % of impressions resulting in engagement | (Engagements ÷ Impressions) × 100     | Content resonance           |
| **Conversion Rate**          | % of clicks resulting in purchases       | (Purchases ÷ Clicks) × 100            | Funnel efficiency           |
| **Purchase Rate**            | % of impressions leading to purchases    | (Purchases ÷ Impressions) × 100       | Reach to conversion         |
| **Avg. Budget per Campaign** | Total budget ÷ Campaign count            |                                       | Budget distribution         |

**🧩 Dataset Information**
Dataset: Meta Ads Performance Dataset
Tables:

ad_events – Fact table capturing impressions, clicks, purchases, etc.
ads – Defines ad details (platform, type, target demographics).
campaigns – Budget and duration details.
users – Demographic and interest details.

Schema:
ad_events → ads → campaigns
ad_events → users

**🧾 Tools & Technologies**
Power BI – Data Visualization
SQL / Excel – Data Cleaning and Transformation
Domain: Digital Marketing / Social Media Analytics

**🖥️ Dashboard Visuals**
Donut Chart: Engagement by Gender
Bar Chart: Engagement by Age Group
Map: Performance by Country
Calendar Heat Map: Monthly Trends
Stacked Column: Weekly Trend by Ad Type
Area Chart: Hourly Activity Pattern
Matrix: Performance by Ad Type & Platform
