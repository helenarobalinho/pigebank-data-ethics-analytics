# Pig E Bank Data Ethics & Analytics Case Study

## Project Summary
This project is a banking analytics case study focused on detecting money laundering risks, analyzing customer churn, and forecasting financial trends.
It uses data mining, predictive modeling, and time-series analysis to support compliance decisions, while also considering ethical issues like bias, privacy, and data security.
The work is based on a simulated bank dataset and shows how to extract useful insights responsibly from financial data.

## Key Questions
- What factors most influence customer churn in a banking environment?
- How do demographics and product usage relate to customer retention?
- Which customer segments show the highest probability of leaving the bank?
- Can a decision tree model effectively identify churn risk patterns?

## Tools Used
- Microsoft Excel
- Descriptive statistics
- Decision tree modeling for churn prediction
- Linear regression analysis
- Time-series analysis (5-year moving average)
- Data ethics frameworks (bias, privacy, security evaluation)

## Methodology
1. **Data Exploration:** Reviewed banking data like customer details, account activity, credit use, product usage and found patterns linked to customer churn and risk behavior
2. **Data Mining & Decision Tree:** Grouped customers by activity, products used, age, location, and gender and built a decision tree to estimate churn probability
3. **Predictive Analytics:** Studied how customer base size relates to fraud alerts using linear regression and checked model accuracy using R² and residual distribution
4. **Time-Series Analysis:** Analyzed 5-year oil price trends using a moving average, compared raw data with smoothed trends and identified long-term patterns while reducing short-term noise
5. **Data Ethics:** Looked at possible bias in data collection and labeling processes and reviewed privacy and security risks in data handling

## Key Findings
- Customer churn is highest among inactive users and single-product customers
- Middle-aged customers and customers in Germany show higher churn rates
- Most financial indicators (balance, salary, credit card ownership) have limited impact on churn
- More customers in the system leads to more fraud alerts (strong regression relationship, R² ≈ 0.86)
- Linear regression is useful for forecasting trends, not classification tasks like fraud detection
- Bias in data collection, labeling, and investigator judgment can distort model outcomes
- Privacy risks include unauthorized access, weak anonymization, and cross-border data exposure

## Recommendations
- Improve customer retention by targeting inactive users, encouraging more product use, and focusing on middle-aged customers
- Strengthen fraud detection by regularly updating data, standardizing investigator scoring, and using diverse, up-to-date datasets
- Enhance data ethics and compliance by enforcing strict access controls, preventing unauthorized data capture, anonymizing outsourced data, and conducting regular bias checks

---
<sub>Author: Helena Robalinho · CareerFoundry Data Analytics Immersion Program</sub>
