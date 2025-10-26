# 🏷️ Metrocar Funnel Analysis (Google Sheets + SQL + Power BI + DAX)

## 📬 Contact
If you’d like to connect or discuss data visualization and analytics:
- 📧 [karyna.avetisova@nure.ua]
- 🔗 [https://www.linkedin.com/in/karina-avetisova/]

## Full presentation: https://drive.google.com/file/d/1E3vxEo5qhlG5wjAGmDHvBoXtpiOoy0b5/view?usp=sharing

## 📋 Project Overview
This project focuses on analyzing the user journey in a ride-sharing app — from the initial app download to the final ride completion and feedback stage.
The goal is to identify conversion rates, drop-off points, and key bottlenecks that affect user engagement and trip completion.
The analysis was performed using SQL, Power BI, and Tableau.

## 🎯 Objectives
1. Build a funnel analysis to visualize each stage of the user journey.
2. Identify where users drop off and quantify the biggest conversion losses.
3. Analyze user behavior patterns by platform, age group, and time factors (day of week, time of day).
4. Provide data-driven recommendations for improving user retention and conversion rates.

## 🧩 Dataset
The dataset includes user and trip-level data, such as:
- User information: platform (iOS / Android / Web), age group
- Trip data: request time, trip status, waiting time, completion flag, revenue
- Event stages: app download → registration → trip request → acceptance → trip start → payment → feedback

## 🛠️ Tools & Technologies
| Tool              | Purpose                                           |
| ----------------- | ------------------------------------------------- |
| **SQL (DBeaver)** | Data extraction and transformation                |
| **Excel**         | Data cleaning and aggregation                     |
| **Power BI**      | Dashboard creation and advanced visualization     |
| **DAX**           | Custom measures and calculated columns            |

## 📈 Key Insights

- The largest drop-off occurs between trip request and trip acceptance, indicating a potential driver availability issue.
- Conversion from payment to feedback is high, meaning engaged users tend to stay active.
- Web users show the lowest retention, while mobile platforms (iOS, Android) perform more consistently.
- The 25–34 age group is the most active and completes the most rides.
- Conversion rates improve slightly during weekends and evening hours, likely due to higher trip intent.

## 📊 Dashboard
An interactive dashboard (https://app.powerbi.com/links/MzGROxqU-I?ctid=7c3c6e36-4292-483f-9d99-13675cceb4a4&pbi_source=linkShare) was built to visualize:

## General Analysis
<img width="1191" height="682" alt="image" src="https://github.com/user-attachments/assets/5411e181-7f98-48aa-a625-a3269ea0cbde" />

Summary:
- The overall conversion rate from app download to completed ride is moderate, with visible drop-offs at multiple stages.
- The largest user engagement loss occurs during the ride request → acceptance stage, suggesting possible driver shortages or long waiting times.
- Despite drop-offs, over half of users who start a trip complete it, showing a stable core of active users.
- The average revenue per user (ARPU) remains consistent across stages, indicating loyal, high-value customers continue using the service.

## Platform Analysis
<img width="1193" height="687" alt="image" src="https://github.com/user-attachments/assets/e89db916-eccc-4942-89bd-175204fe64c2" />
<img width="1192" height="682" alt="image" src="https://github.com/user-attachments/assets/f34aa529-3b32-4d99-98d3-3756bdc4be09" />

Summary:
- iOS users generate the highest number of rides and show the best completion rate.
- Android users are active but have slightly lower conversion — possibly due to device segmentation or UX issues.
- Web platform has the lowest retention and engagement; users often drop off before completing their first trip.
- Recommendation: focus marketing and UX improvements on Android and Web to balance platform performance.

## Drop-Off Points
<img width="1191" height="688" alt="image" src="https://github.com/user-attachments/assets/d8fc4dfa-a51b-4924-9e7f-354572d805d7" />

Summary:
- The most significant bottleneck is between “Trip Requested” → “Trip Accepted” (conversion below 70%).
- Potential causes:
  - Driver unavailability at specific times or areas.
  - Long waiting times leading to user cancellations.
- A smaller but relevant drop is observed after payment, indicating users might not be encouraged to leave feedback.
- Recommendation:
  - Optimize driver dispatch algorithms.
  - Introduce real-time status updates or loyalty incentives to reduce cancellations.
  
## Age Category Analysis
<img width="1192" height="689" alt="image" src="https://github.com/user-attachments/assets/a4990be8-2b98-4c32-861c-4b7655c3ecad" />

Summary:
- The 25–34 age group is the most active segment, completing the majority of successful rides.
- 18–24 users show strong engagement but a higher drop-off rate, possibly due to price sensitivity or convenience expectations.
- Older age segments (45+) have low engagement, indicating untapped potential for targeted offers or simpler UX flows.
- Recommendation:
  - Personalize campaigns by age segment.
  - Test student discounts or simplified booking flows for younger users.

## Map Activity
<img width="1191" height="685" alt="image" src="https://github.com/user-attachments/assets/a684b333-0236-45df-81f1-3cabb3b41d91" />

Summary:
- The map visualization shows high booking density in central and high-traffic zones, confirming urban usage dominance.
- Activity peaks in evening hours and weekends, aligning with leisure and social mobility patterns.
- Some areas show frequent cancellations or long wait times, potentially due to poor driver coverage.
- Recommendation:
  - Use geospatial data to rebalance driver distribution.
  - Implement surge pricing or incentives in low-supply zones.

## 🧠 What I Learned
- How to structure and visualize a multi-step funnel in both Power BI and Tableau.
- How to use DAX to calculate dynamic KPIs (conversion %, completion rate, ARPU).
- How to design executive-level dashboards focusing on clarity and insight rather than visual clutter.
- The importance of user segmentation and behavioral metrics in product performance analysis.
