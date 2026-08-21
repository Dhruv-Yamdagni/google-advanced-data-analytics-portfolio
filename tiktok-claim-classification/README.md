# TikTok: Video Claim vs. Opinion Classification

## Business Scenario
TikTok's moderation team handles millions of daily user reports. To optimize reviewer workflows, this project analyzes user engagement signals to automatically distinguish objective claims from subjective personal opinions.

## Project Roadmap
- [x] **Course 2: Data Exploration & Slicing** — DataFrame ingestion, summary statistics, and null-value handling.
- [x] **Course 3: Exploratory Data Analysis** — Comparative engagement analysis across claim statuses and verification tiers.
- [ ] **Course 4: Hypothesis Testing (Verified vs. Unverified)** *(Upcoming)*
- [ ] **Course 5: Logistic Regression Modeling** *(Upcoming)*
- [ ] **Course 6: Machine Learning Tree Models** *(Upcoming)*

## Key Findings (Courses 2 & 3)
* **Engagement Discrepancy:** Videos categorized as `claim` receive substantially higher average view counts, shares, likes, and downloads compared to `opinion` videos.
* **Verification Status:** Unverified accounts publish a significantly higher proportion of claim-type content compared to verified creators.
* **Data Quality:** Missing values (~298 rows) were isolated and analyzed; they are missing completely at random (MCAR) across engagement metrics.

## Visualizations
*Add your exported Seaborn plots here:*
* `![Claim vs Opinion Engagement](visualizations/claim_vs_opinion_engagement.png)`
* `![Author Status Distribution](visualizations/author_status_distribution.png)`
