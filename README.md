# Netflix Churn Analysis
- This project builds an end-to-end machine learning pipeline to predict customer churn for a subscription-based digital service.
- The goal is to identify at-risk users early using behavioral, engagement, and subscription features.
#
**Key objectives:**
- Analyze user behavior patterns linked to churn
- Engineer meaningful engagement features
- Train and evaluate regression model
- Interpret model outputs for business analytics report

## Dataset Overview:
[Netflix-Style Synthetic Dataset]([url](https://www.kaggle.com/datasets/sayeeduddin/netflix-2025user-behavior-dataset-210k-records/data)) 
- **Dataset Overview** - This synthetic dataset simulates a Netflix-style streaming platform with realistic user behavior, content catalog, and engagement metrics. Perfect for machine learning, data science, and analytics projects.

- **Key Features of "users.csv"** - 10,300 total records with User demographics, subscription plans, regional data
- **Key Features of "watch_history.csv"**	- 105,000 total records	with viewing sessions with device, quality, progress data
- **Key Features**
- - The Final pruned dataset consists of:
  - Size: 8,431 users
  - 17 engineered features
  - Target Variable:
  - - churn (1 = churned, 0 = retained)
## Feature Groups
| Category           | Features                                           |
| ------------------ | -------------------------------------------------- |
| Demographics       | age, gender, country                               |
| Subscription       | subscription_plan, monthly_spend                   |
| Engagement         | avg_session_minutes, num_sessions, watch_per_day   |
| Retention Signals  | tenure_days, days_since_last_watch                 |
| Content Completion | completion_rate                                    |
| Engineered Buckets | watch_bucket, inactivity_bucket, completion_bucket |
| Value Metrics      | value_ratio                                        |
#

