# Fraud-Adjusted-Customer-Lifetime-Value-CLV-Analytics


🚀 Project Overview

In fintech and digital banking, traditional Customer Lifetime Value (CLV) models are misleading because they ignore fraud losses, customer churn after fraud, and operational costs.
This project builds a Fraud-Adjusted CLV Analytics system that helps leadership answer:

Are we growing profitably, or are fraud and risk eroding customer value?

The solution combines SQL-ready business logic, advanced Power BI DAX, and executive-grade dashboards to deliver actionable fraud, risk, and customer profitability insights.


🧠 Business Problem

Financial institutions face three critical challenges:

Revenue growth hides fraud impact
High transaction volume may look healthy while fraud silently destroys value.

Fraud controls can cause customer churn
Over-blocking and false positives lead to customer loss, especially in high-value segments.

One-size-fits-all fraud rules fail
Risk tolerance varies by channel, income band, and customer risk profile.



🗂️ Data Model (Synthetic, Realistic)

Tables Used

customers – demographics, income band, risk profile

transactions – transaction history, channels, fraud flags

fraud_losses – fraud amounts, fraud types, loss dates

support_costs – monthly customer servicing cost

calendar – time intelligence

Dataset size: 5,000+ customers | 100,000+ transactions




📈 Dashboards Built
1️⃣ Executive Overview

Audience: CXOs, Business Heads

Key Insights:

Total Revenue & Net Risk-Adjusted Profit

Fraud Impact %

Fraud vs Revenue Growth Ratio

High-Risk Customer %

Risk-Adjusted Revenue Growth

Executive insight banner (dynamic narrative)

📌 Purpose:
Quickly assess whether growth is healthy or risk-driven.

2️⃣ Customer Risk & Profitability

Audience: Risk Strategy, Product Teams

Key Insights:

Risk-Adjusted Customer Profit

Customer Risk Burden Index

High-Risk Revenue Dependency

Profit-to-Risk Tradeoff

Risk migration (YoY)

Acquisition vs churn analysis

Channel-wise customer loss after fraud

📌 Purpose:
Understand where risk is concentrated and how it affects profitability.

3️⃣ Fraud Impact Insights

Audience: Fraud Ops, Risk Ops

Key Insights:

Fraud cost per legit transaction

Fraud rate %

Fraud from new vs repeat customers

Channel-wise fraud loss %

Post-fraud customer retention vs loss

Fraud type contribution

Customer-level decision table (EXIT / SAVE / MONITOR / UPSSELL)

📌 Purpose:
Turn fraud analytics into daily operational decisions.

🧮 Advanced Analytics & DAX Highlights

Fraud-Adjusted CLV

CLV Percentile-based customer ranking

Fraud Exposure %

Fraud Velocity (loss speed)

Fraud-Driven Churn Risk

Risk-Adjusted CLV

Decision Engine using percentile logic

Channel-wise post-fraud customer flow (retained vs lost)

✔ Avoids hard-coded thresholds
✔ Adapts automatically to portfolio size
✔ Production-ready logic

🎯 Decision Intelligence Engine

Each customer is classified into one of four actions:

Decision	Meaning
EXIT	High fraud + low value
SAVE	Valuable but risky
MONITOR	Stable customers
UPSELL	High value, low risk

This enables precision fraud strategy, not blanket blocking.

🏆 Key Business Outcomes

Identified channels causing highest customer loss after fraud

Quantified revenue lost due to over-blocking

Highlighted high-risk revenue dependency

Prevented misclassification of profitable customers as risky

Delivered actionable customer-level fraud decisions

🛠️ Tools & Skills Used

Power BI – Advanced DAX, Time Intelligence, Executive Dashboarding

SQL (logic-ready) – Aggregations, segmentation, fraud analytics

Data Modeling – Star schema, risk analytics design

Business Analytics – Fraud, Risk, CLV, Retention

Storytelling – Executive-ready narratives

📌 Who This Project Is For

Fraud Analyst

Risk Analyst

Revenue Analyst

Senior Data Analyst (Finance / Fintech)

Business Analyst (Risk / Payments)

📎 How to Use This Repository

Review dashboard PNGs for visual design

Explore DAX measures for decision logic

Use datasets to recreate the model in Power BI

Extend logic for YoY, MoM, or real-time fraud use cases

✨ Final Note

This project demonstrates how fraud analytics, customer lifetime value, and business decisioning come together in real fintech environments.
It goes beyond charts to deliver risk-aware, profit-focused decisions.
