# PhonePe Payment Insights Dashboard | Power BI

**🌟 Project Overview**

The PhonePe Payment Insights Dashboard is an end-to-end Power BI analytics project designed to monitor digital payment transactions, total payment value, Month-over-Month (MoM) growth, payment success rates, user demographics, and service-level usage trends.

The dashboard transforms raw user and transaction data (`All_Users` and `All_Transactions`) into an interactive visual report featuring a star-schema data model, a dedicated `_Measures` table, a `Date_Table` for time intelligence, dynamic slicers (`Month`, `Payment_Status`), and custom hover tooltips (`Tooltip1`, `Tooltip2`).

**📊 Business Problem**

Digital payment and fintech teams need clear visibility into transaction volume, payment value growth, failure rates, user age segments, and service category performance (`Loans`, `Insurance`, `Money Transfer`, `Recharge & Bills`).

Reviewing raw transaction and user records manually makes it difficult to spot Month-over-Month shifts, evaluate success rates, or compare weekday versus weekend payment activity.

This project addresses that challenge by consolidating cleaned data, DAX measures, and interactive visuals into a single Power BI report.

**🎯 Key Objectives**

1. Track core KPIs (`Total Transactions`, `Total Value`, `Unique Users`, and `Successful Rate`) along with Month-over-Month (`MOM%`) growth metrics.
2. Monitor monthly transaction value trends (`Transactions Over Time` by `Month`).
3. Analyze user distribution across age groups (`Age Segment Contribution`).
4. Compare transaction value across services (`Service Transaction Value Analysis`) and top users (`Top 5 Users by Transaction Value`).
5. Evaluate `Weekday v/s Weekend Usage` and monthly `Total Transaction by Month and Payment_Status` (`Failed`, `Pending`, `Successful`).
6. Enable dynamic filtering using `Month` and `Payment_Status` slicers and custom report tooltips (`Tooltip1`, `Tooltip2`).

**📁 Data Source**

**Source:** PhonePe Transaction & User Dataset (`All_Users` — 107,658 records; `All_Transactions` — 300,000 records).

**📝 Tools and Technologies**

1. **Microsoft Power BI** - Data cleaning in Power Query, star-schema modeling (`All_Users`, `All_Transactions`, `Date_Table`), custom tooltips, slicers, and dashboard layout.
2. **DAX Measures** - Time-intelligence and KPI calculations (`Total Transaction`, `Total Transaction Value`, `Unique Users`, `Successful Transactions`, `Success Rate`, `Total Trans PM`, `Total Trans MOM%`, `Trans Value PM`, and `Trans Value MOM%`).
3. **Power BI Visuals** - KPI cards, line chart, donut chart, bar/column charts, stacked column chart, slicers, and report tooltips.

**🚀 Key Performance Indicators (KPIs)**

The dashboard highlights four primary executive KPIs:

1. **Total Transactions:** 300K (`Total Trans MOM%`: 8.97%)
2. **Total Value:** 3.47bn (`Trans Value MOM%`: 8.98%)
3. **Unique Users:** 108K
4. **Successful Rate:** 96.00%

**📈 Dashboard Visualizations**

![Dashboard Screenshot](Images/final_dashboard.png)

**✅ Conclusion**

The dashboard supports data-driven payment analytics by helping teams track Month-over-Month growth, monitor payment reliability, understand demographic and service-level usage, and compare weekday versus weekend transaction patterns.