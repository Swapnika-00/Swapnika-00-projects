# Optimizing Employee Performance and Benefit Programs Through Data-Driven Insights

![SQL](https://img.shields.io/badge/SQL-PostgreSQL-blue) 
![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-green) 

---

## Table of Contents
1. [Company & Business Context](#1-company--business-context)
2. [Business Problem Statement](#2-business-problem-statement)
3. [Project Rationale](#3-project-rationale)
4. [Aims & Objectives](#4-aims--objectives)
5. [Dataset Description](#5-dataset-description)
6. [Tools & Technologies](#6-tools--technologies)
7. [Data Cleaning & Preparation](#7-data-cleaning--preparation)
8. [Analysis Performed](#8-analysis-performed)
9. [Dashboards](#9-dashboards)
10. [Key Insights & Findings](#10-key-insights--findings)
11. [Recommendations](#11-recommendations)
12. [Challenges & Learnings](#12-challenges--learnings)
13. [Conclusion](#13-conclusion)

---

## 1. Company & Business Context

| Attribute | Details |
|---------|---------|
| **Company Name** | Grand Meridian Hotel |
| **Location** | England |
| **Founded** | 2004 |
| **Rooms** | 182 guest rooms |
| **Key Milestones** | 2008: Opened a 40-seat meeting and event space to cater to business groups<br>2013: Added spa services to attract weekend leisure guests.<br>2019: Introduced a loyalty program to boost repeat bookings. |

The hotel serves both Corporate and Leisure guests and generates revenue through:
- Room bookings
- Dining services
- Spa treatments
- Meetings & events

---

## 2. Business Problem Statement

Despite stable occupancy, management lacked visibility into true revenue drivers across guest segments.
Key Challenges:
1.	No Segment-Level Profit Visibility
Revenue was tracked, but not analyzed by guest type with ancillary services included.
2.	Season-Based Pricing Only
Pricing decisions were largely seasonal, not revenue-optimized.
3.	Unclear Marketing ROI
Marketing spend was split between corporate and leisure segments without performance evidence.
4.	Underutilized Loyalty Data
Loyalty membership impact on revenue and repeat bookings was not evaluated.

---

## 3. Project Rationale

Analysing of how seasonal demand influences room bookings and ancillary services (spa, dining, events) and which guest type (corporate or leisure) is most profitable. By examining the seasonality and revenue of each segment, GMH can make more data-driven decisions on pricing, marketing, and service offerings.
Top 5 Strategic Reasons for the Project:
- Better Pricing Decisions: Identify where price adjustments will drive maximum revenue.
- Improved Marketing ROI: Focus campaigns on guests that bring higher margins.
- Optimised Operations: Align staffing and services with profitable demand patterns.
- Enhanced Customer Targeting: Use loyalty and booking data to tailor offers.
- Sustainable Revenue Growth: Maximise revenue without relying solely on increasing occupancy.

---

## 4. Aims & Objectives

To perform Seasonal Revenue Analysis & Pricing Optimization to help the hotel:
- Identify the most profitable guest segments
- Understand seasonal booking patterns
- Evaluate pricing adjustment scenarios
- Improve marketing allocation decisions

---

## 5. Dataset Description

| Feature | Details |
|-------|--------|
| **Data Source** | Internal booking Database|
| **Records** | ~7000 |
| **Key Columns** |Booking ID, Check-in/Check-out Date, Room Type, Seasonal Adjustment, Discount, Booking Channel, Guest Type, Loyalty Member, Rooms Booked, Ancillary Service type, Service Revenue, Room sub type ID, Base Rate, Peak Adjustment Factor, Moderate Adjustment Factor|
| **Data Issues** | Missing values, inconsistent formats, incomplete ancillary revenue tagging|

---

## 6. Tools & Technologies

- **SQL** → Data cleaning, transformation, revenue calculations
- **Power BI** → KPI dashboards, trend visualization, what-if analysis


---

## 7. Data Cleaning & Preparation

-  Standardized date formats
-  Removed null/invalid booking entries
-  Created calculated columns:
    •	Total Room Revenue
    •	Total Service Revenue
    •	Revenue per Segment
    •	Average Daily Rate (ADR)
    •	Occupancy Rate
- Built season classification logic
-  Structured data model for dashboard performance

---

## 8. Analysis Performed

1.	**Revenue by Guest Segment**
Measured total revenue contribution from:
-	Corporate guests
-	Leisure guests
-	Loyalty vs Non-loyalty
2.	**Seasonal Trend Analysis**
Analysed:
- Monthly occupancy
- Monthly revenue
- ADR trends
- Peak vs shoulder season performance
3.	**Ancillary Service Revenue Analysis**
Compared service spending patterns:
- Events
- Dining
- Spa
4.	**Pricing What-If Scenario**
Simulated revenue impact of percentage-based price increases during peak

---

## 9. Dashboards
Interactive dashboards visualize trends and insights. These are hosted on the portfolio website for real-time access.

---

## 10. Key Insights & Findings

-	Leisure guests generate higher total revenue than corporate guests.
-	 Corporate guests contribute proportionally more to event and dining services, but ancillary revenue remains a small share of total revenue.
-	December shows the highest occupancy and revenue, indicating strong peak demand.
-	ADR drops noticeably in May, presenting a pricing optimization opportunity.
-	Loyalty members account for less than 25% of total bookings, showing growth potential.

---

## 11. Recommendations

1. Revenue Optimization
Increase room rates during December peak season to maximize revenue.
2. Marketing Strategy
- Promote corporate dining + event packages
- Target first-time customers with loyalty incentives
- Increase luxury room promotions during shoulder months
3. Ancillary Revenue Strategy
Since room revenue dominates total income:
- Either reduce operational focus on low-margin services
OR
- Bundle spa/dining with room packages to improve service uptake.

---

## 12. Challenges & Learnings

Challenges
- Inconsistent raw data formatting
- Missing ancillary revenue fields
- Designing intuitive dashboards for non-technical stakeholders
Learnings
- Strengthened SQL data modeling skills
- Improved KPI storytelling in Power BI
- Gained experience in translating business problems into measurable metrics


---

## 13. Conclusion

This project demonstrates how data analytics can move a hotel from seasonal pricing assumptions to evidence-based revenue optimization.
By leveraging SQL for structured data preparation and Power BI for dynamic insights, the analysis provides actionable recommendations to improve revenue strategy, marketing efficiency, and long-term growth.
---
