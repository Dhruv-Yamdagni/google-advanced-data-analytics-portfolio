# Waze: Driver Churn Analysis & Retention Strategy

## Business Scenario
Waze is looking to reduce user churn by understanding driver app usage patterns. This project investigates behavioral telemetry (sessions, driving days, distance driven) to differentiate retained users from churned users.

## Project Roadmap
- [x] **Course 2: Data Cleaning & Validation** — Data parsing, variable inspection, and summary metrics.
- [x] **Course 3: Exploratory Data Analysis** — Feature distribution, IQR outlier analysis, and churn cross-tabulation.
- [ ] **Course 4: Statistical Testing & Analysis** *(Upcoming)*
- [ ] **Course 5: Binomial Logistic Regression** *(Upcoming)*
- [ ] **Course 6: Machine Learning Churn Predictor** *(Upcoming)*

## Key Findings (Courses 2 & 3)
* **Activity Skewness:** Metrics like `driven_km_drives` and `sessions` exhibit long right tails; heavy power users represent a disproportionate volume of total app mileage.
* **Churn Signals:** Users who drive fewer days per month (`driving_days`) show a significantly higher probability of churning, suggesting engagement frequency is a primary retention indicator.
* **Device Independence:** Churn rates are nearly identical across iPhone and Android platforms, indicating churn is driven by user habits or external factors rather than OS-specific bugs.

## Visualizations
*Add your exported Seaborn plots here:*
* `![Churn vs Retention Boxplot](visualizations/churn_vs_retention_boxplot.png)`
* `![Driving Days Distribution](visualizations/driving_days_distribution.png)`
