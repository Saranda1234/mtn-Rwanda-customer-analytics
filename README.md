# MTN Rwanda Customer Dashboard | Customer Churn Analysis

## Project Overview
Customer churn analysis dashboard built using Apache Superset,
analyzing behavioral and service data for **7,043 MTN Rwanda subscribers**
to identify churn patterns across service types, contract types, and customer segments.

## Dashboard Preview
![MTN Rwanda Dashboard](screenshots/dashboard.png)

## Key Metrics
| Metric | Value |
|--------|-------|
| Total Customers | 7,043 |
| Overall Churn Rate | 26.5% |
| Churned Customers | ~1,866 |
| Active Customers | ~5,177 |

## Charts & Analysis

### 1. Total Customers & Churn Rate KPIs
![KPIs](screenshots/kpis.png)
Overall snapshot of the subscriber base and churn percentage.

### 2. Churned vs Active Customers
![Churned vs Active](screenshots/churned_vs_active.png)
Pie chart showing the split between churned and retained customers.

### 3. Senior vs Non-Senior Customers
![Senior vs Non-Senior](screenshots/senior_vs_nonsenior.png)
Segment analysis comparing churn behavior between senior and non-senior subscribers.

### 4. Churn by Internet Service
![Churn by Internet Service](screenshots/churn_by_internet.png)
Bar chart showing churn distribution across different internet service types.

### 5. Churn by Contract Type
![Churn by Contract Type](screenshots/churn_by_contract.png)
Bar chart showing how contract type influences churn rate.

## Key Insights
- Customers on **month-to-month contracts** show significantly higher churn
- **Fiber optic** internet service users have higher churn than DSL users
- **Senior customers** represent a smaller segment but show distinct churn patterns

## Tools Used
| Tool | Purpose |
|------|---------|
| Apache Superset | Dashboard & visualization |
| SQL | Data querying & aggregation |
| Docker | Local deployment |
| Excel | Data preparation & cleaning |

## Files in This Repo
- `mtn-rwanda-customer-dashboard.pdf` — Full dashboard export
- `screenshots/` — Individual chart screenshots

## Author
**Ndayambaje Alexis**
Data Analytics Intern — MTN Rwanda
📧 alexsaranda2@gmail.com
🔗 [GitHub Profile](https://github.com/Saranda1234)
