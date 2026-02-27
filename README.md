# Product-Performance-Feature-Impact-Analysis
Identifying which product features drive value and reduce churn risk **Author: Justice Analyst** | Last Updated: 03 Feb 2026

##  Project Overview

This Power BI dashboard project analyses product feature performance, customer churn risk, and sentiment feedback for a telecom dataset. It is structured across **three analytical pages** designed to help identify which features retain customers, flag high-risk accounts, and surface the key drivers of dissatisfaction.

## Repository Contents

| File | Description |
| `Screenshot_Feature_Insights.png` | Page 1 – Feature adoption, revenue by feature, and retention rates |
| `Screenshot_Churn_Risk.png` | Page 2 – Churn analysis by tenure, contract type, and high-risk customer table |
| `Screenshot_Customer_Voice.png` | Page 3 – Sentiment distribution, complaint keywords, and churn by sentiment |

## 📊 Key Metrics
| Metric | Value |
| Total Customers | 7,032 |
| Avg Revenue per User (ARPU) | $64.80 |
| Overall Churn Rate | 26.58% |
| Overall Retention Rate | 73.42% |
| Total Revenue by Feature | $80.19M |
| % Negative Sentiment | 2.94% |
| Churn Rate (Negative Sentiment) | 79.23% |

##  Dashboard Pages

### Page 1 – Feature Insights
Focuses on product feature adoption, revenue contribution, and retention rates per feature.

- **PhoneService** is the most widely adopted feature (90.33%) and generates the highest revenue ($12.29M)
- **OnlineSecurity** and **TechSupport** are the least adopted (28.65% and 29.01%) but have the **highest retention rates** — 85.36% and 84.80% respectively
- Customers using more features show consistently **lower churn rates**, confirming deeper product engagement drives loyalty
- **StreamingTV** has the lowest retention rate among all features (69.89%)

### Page 2 – Churn & Risk
Detects high-risk customers and analyses churn patterns by tenure and contract type.

- **New customers** churn at the highest rate (99.04%), indicating a critical early engagement gap
- **Month-to-month contracts** have the highest churn (98.81%), while **two-year contracts** churn at just 76.19%
- Avg monthly charges for churned customers: **$74.44**
- A **High-Risk Customer table** combines tenure, revenue, feature usage, and sentiment to support targeted retention actions

### Page 3 – Customer Voice
Links customer feedback and sentiment directly to churn behaviour and feature experience.

- Only **2.94%** of feedback is negative, yet those customers churn at **79.23%** — far above neutral (26.92%) and positive (18.21%) segments
- Top complaint themes: **service quality, internet reliability, and pricing**
- **PhoneService** has the highest volume of negative feedback (176 negative mentions)
- **MultipleLines** has the most neutral feedback (2,235), suggesting low emotional engagement

##  Key Insights

- Features with **low adoption but high retention** (OnlineSecurity, TechSupport) are underutilised and represent a major upsell opportunity
- **Contract length is one of the strongest churn predictors** — encouraging longer commitments could significantly reduce churn
- **Sentiment is a leading indicator of churn** — identifying and acting on negative feedback early can prevent loss
- Increasing feature engagement per customer is associated with lower churn and higher lifetime value

## ✅ Recommendations
1. **Promote OnlineSecurity and TechSupport** — underadopted but highest-retention features; strong upsell candidates
2. **Incentivise longer-term contracts** — month-to-month customers carry the highest churn risk
3. **Strengthen new customer onboarding** — near-100% churn in the new tenure group signals a critical early engagement gap
4. **Act on negative sentiment immediately** — 79.23% churn rate among dissatisfied customers demands a fast feedback response loop
5. **Address internet reliability and pricing complaints** — top drivers of dissatisfaction from keyword analysis

##  Tools Used
- **Power BI** — Dashboard design, DAX measures, and interactive visualisations
- **Telecom Customer Dataset** — 7,032 customer records across features, charges, contracts, and feedback

##  Author
**Justice Analyst**
- Linkedin [@JusticeAnalyst](https://twitter.com/JusticeAnalyst)
- Twiiter [@JusticeNelson50](https://twitter.com/JusticeNelson50)
