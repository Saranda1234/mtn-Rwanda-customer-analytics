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
| Senior Customers | ~1,140 |
| Non-Senior Customers | ~5,900 |

## Charts & Analysis

### 1. Total Customers & Churn Rate KPIs
![KPIs](screenshots/kpis.png)
High-level snapshot showing 7,043 total subscribers with an overall churn rate of 26.5%.

### 2. Churned vs Active Customers
![Churned vs Active](screenshots/churned_vs_active.png)
Pie chart showing the proportion of churned (Yes) vs retained (No) customers.

### 3. Senior vs Non-Senior Customers
![Senior vs Non-Senior](screenshots/senior_vs_nonsenior.png)
Segment breakdown — ~1,140 senior customers vs ~5,900 non-senior customers.

### 4. Churn by Internet Service
![Churn by Internet Service](screenshots/churn_by_internet.png)
Bar chart comparing churn across DSL, Fiber Optic, and No internet service subscribers.
Fiber optic users show the highest churn volume.

### 5. Churn by Contract Type
![Churn by Contract Type](screenshots/churn_by_contract.png)
Bar chart showing churn across Month-to-month, One year, and Two year contracts.
Month-to-month contracts have significantly higher churn.

### 6. Revenue by Payment Method
![Revenue by Payment Method](screenshots/revenue_by_payment.png)
Donut chart showing revenue distribution across different payment methods.

### 7. Customers by Tenure
![Customers by Tenure](screenshots/customers_by_tenure.png)
Line chart tracking customer count across tenure duration (0–70 months).
Shows a spike in new customers and a recovery at long tenure — indicating loyalty patterns.

## Key Insights
- **Month-to-month** contract customers churn at a much higher rate than yearly contracts
- **Fiber optic** users show higher churn than DSL users
- Customers with **longer tenure (60–70 months)** show strong retention recovery
- **Senior customers** (~16%) show distinct behavioral patterns worth targeting

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
