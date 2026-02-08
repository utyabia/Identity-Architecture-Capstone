Identity Architecture: Global Superstore Analytical Report
📌 Project Overview
This Capstone Project is a comprehensive analysis of the Global Superstore dataset through the lens of Identity Architecture. The goal was to treat data points—such as customers, regions, and products—as unique identities within a business ecosystem to uncover patterns in profitability, sales trends, and operational efficiency.

🎯 Objective & Goal
Objective: To derive a complete identity framework by analyzing user segments, geographic distributions, and transaction behaviors.

Goal: To provide actionable insights via an interactive dashboard that identifies high-risk (unprofitable) identities and predicts future growth.

🛠️ Data Cleaning & Analytical Talent
During the preparation phase, I encountered significant data quality issues that required analytical intervention:

The Date Challenge: The Order.Date and Ship.Date columns were corrupted (showing 00:00.0). I utilized my analytical talent to reconstruct a functional timeline using the Year and weeknum columns, allowing for accurate time-series analysis.

Architectural Streamlining: Removed irrelevant columns like 记录数 (ji_lu_shu) and Row.ID to focus strictly on business-critical identities.

Data Sanitization: Standardized naming conventions across Market and Segment to ensure a "Single Source of Truth."

📊 Analytical Insights (The 4 Types of Analytics)
1. Descriptive Analytics (What happened?)
Identity Distribution: I mapped the volume of unique Customer IDs across 7 global markets.

Product Performance: Identified the top-performing Product Categories by Sales volume.

2. Diagnostic Analytics (Why did it happen?)
Profitability Gaps: Analyzed why certain markets show negative profit despite high sales. I discovered a direct correlation between high Discount rates and eroded profit identities in the EMEA region.

3. Predictive Analytics (What might happen?)
Sales Forecasting: Using the reconstructed Year and weeknum timeline, I established a trend line to forecast sales trajectories for the next fiscal cycle.

4. Prescriptive Analytics (What should we do?)
Targeting Strategy: Identified the top 10 most unprofitable customer identities. I recommend a revision of pricing strategies or a reduction in shipping subsidies for these specific accounts to salvage margin.
