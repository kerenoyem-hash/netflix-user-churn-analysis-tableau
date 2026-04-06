#Netflix User Behavior & Churn Analysis


## Project Overview
This project analyzes user behavior and churn patterns in a Netflix-like subscription dataset. The goal is to understand what drives user churn and identify key factors that influence retention.
By leveraging data visualization and calculated metrics, this dashboard provides actionable insights into user engagement, subscription behavior, and churn risk.
--- 
## Dataset
•	Source: Kaggle
•	Dataset: Netflix User Watching Behavior Dataset
•	Records: 50,000 users
The dataset includes user demographics, subscription details, engagement metrics, and churn indicators.
---
## Objectives
•	Analyze user churn patterns
•	Identify high-risk user segments
•	Compare churn across subscription types
•	Understand the relationship between engagement and churn
•	Provide actionable business insights
--- 
## Tools Used
•	Tableau Public (Data Visualization)
•	Excel / CSV (Data Source)
--- 
## Data Preparation
•	Removed duplicate records
•	Verified data types (numerical and categorical fields)
•	Converted churn field into binary format (Yes/No → 1/0)
•	Created calculated fields for analysis
--- 
## Key Calculations
🔹 Churn Rate
AVG(Churned Users)
Where:
•	1 = Churned
•	0 = Active
 
🔹 Engagement Score
A weighted metric combining:
•	Watch Time (40%)
•	Sessions per Week (30%)
•	Completion Rate (30%)
 
🔹 Recency Segmentation
Users were grouped based on activity:
•	Active Recently → ≤ 7 days
•	At Risk → 8–30 days
•	Dormant → 30+ days
--- 
## Dashboard Features
🔝 KPIs
•	Total Users
•	Churn Rate (%)
•	Average Engagement Score
•	Retention Rate (%)
--- 
## Visual Analysis
•	Churned Users by Subscription Type
•	Churn Rate by Country (Map)
•	Device Usage Distribution
•	Engagement Level vs Churn
•	Recency vs Churn Analysis
--- 
## Key Insights
1️⃣ Subscription Behavior
Standard users contribute the highest number of churned users due to their larger user base.
However, Premium users show a higher churn rate, indicating a greater likelihood of leaving.
 
2️⃣ Engagement Impact
Users with low engagement levels have significantly higher churn rates.
Highly engaged users contribute more churn in total numbers due to volume, but are less likely to churn proportionally.
 
3️⃣ Recency Effect
Dormant users are the most likely to churn, confirming that inactivity is a strong indicator of churn risk.
 
4️⃣ Device Usage
Mobile devices show the highest usage share, indicating a strong preference for mobile streaming.
---
## Business Recommendations
•	Improve retention strategies for Premium users
•	Target low-engagement users with personalized content
•	Re-engage dormant users through notifications or promotions
•	Optimize mobile experience for better user satisfaction
---
## Conclusion
This analysis highlights that churn is influenced by multiple factors, including engagement, subscription type, and user activity. By focusing on high-risk segments, businesses can improve retention and enhance overall user experience.
---
## Links
•	📊 Dataset: https://www.kaggle.com/datasets/rhythmghai/netflix-user-watching-behavior-dataset
•	💼 LinkedIn: https://www.linkedin.com/in/keren-oyem
•	💻 GitHub: https://github.com/kerenoyem-hash
---
## Author
Keren Oyem
Aspiring Data Analyst | Passionate about data-driven decision making

