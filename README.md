# MTN Rwanda Customer Dashboard | Customer Churn Analysis

## Project Overview
Customer churn analysis dashboard built using Apache Superset,
analyzing behavioral and service data for **7,043 MTN Rwanda subscribers**
to identify churn patterns across service types, contract types, and customer segments.

## Dashboard Preview
<img width="587" height="377" alt="image" src="https://github.com/user-attachments/assets/418942bf-2c80-437b-83a7-663ba8c76683" />
<img width="595" height="390" alt="image" src="https://github.com/user-attachments/assets/4ef880bf-0972-4a92-a14e-9ffbf1259468" />



## Key Metrics
| Metric | Value |
|--------|-------|
| Total Customers | 7,043 |
| Overall Churn Rate | 26.5% |
| Senior Customers | ~1,140 |
| Non-Senior Customers | ~5,900 |

## Charts & Analysis

### 1. Total Customers & Churn Rate KPIs
<img width="302" height="167" alt="image" src="https://github.com/user-attachments/assets/bf1eedf7-649b-46a2-9f45-1d434f7ab09a" />

High-level snapshot showing 7,043 total subscribers with an overall churn rate of 26.5%.

### 2. Churned vs Active Customers
<img width="297" height="161" alt="image" src="https://github.com/user-attachments/assets/100572de-314d-4fdb-8196-5074285a8b81" />

Pie chart showing the proportion of churned (Yes) vs retained (No) customers.

### 3. Senior vs Non-Senior Customers
<img width="293" height="161" alt="image" src="https://github.com/user-attachments/assets/db2729ac-791e-448b-9f52-c094b5dd7630" />

Segment breakdown — ~1,140 senior customers vs ~5,900 non-senior customers.

### 4. Churn by Internet Service
<img width="457" height="311" alt="image" src="https://github.com/user-attachments/assets/a7d26728-72b8-4e4f-93a3-fc2d3d11ed53" />

Bar chart comparing churn across DSL, Fiber Optic, and No internet service subscribers.
Fiber optic users show the highest churn volume.

### 5. Churn by Contract Type
<img width="448" height="307" alt="image" src="https://github.com/user-attachments/assets/bcf5d32a-09f9-4fac-a396-1728aadfacbd" />

Bar chart showing churn across Month-to-month, One year, and Two year contracts.
Month-to-month contracts have significantly higher churn.

### 6. Revenue by Payment Method
<img width="455" height="310" alt="image" src="https://github.com/user-attachments/assets/b9dad29e-0cfb-45a2-9826-92d4d151fb18" />

Donut chart showing revenue distribution across different payment methods.

### 7. Customers by Tenure
<img width="451" height="305" alt="image" src="https://github.com/user-attachments/assets/618b26d3-cff0-4e8e-ba33-ca4e807866d2" />

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
