# Churn Analysis Project

## Description
This project analyzes the reasons behind the decline in user engagement with our website and assesses the extent of this issue. The analysis revealed a **Customer Churn Rate of 16.84%** with **31% of customers dissatisfied** with the service.

## Data Cleaning
- Handled missing values by replacing nulls with the column's mean value, as no outliers were present.
- Merged the "phone" and "mobile phone" fields into a single "phone" field.

## KPIs
- **Customer Churn Rate**: 16.84%
- **Repeat Purchase Rate**: 79%
- **Net Promoter Score**: 8%
- **Customer Feedback and Complaint Rate**: 28%
- **Average Customer Tenure**: 10.18%

## Insights
- **Churn Rate and Device Usage**: Churn increases with the number of devices used. This could be due to login issues, device-related feature discrepancies, or user experience problems.
- **Coupon Usage**: Churning customers rarely use coupons, and coupon usage decreases after 30 orders due to fixed coupon values. Offering personalized coupons and loyalty programs could help retain customers.
- **Engagement**: Churning customers spend significantly less time on the website, approximately 50,000 hours less than active users. This could indicate lower engagement or poor user experience.

## Customer Segmentation
- **Cities**: Most orders come from major cities, suggesting opportunities for targeted marketing.
- **Demographics**: Single customers show higher churn rates compared to divorced customers, who have the lowest churn rate.
- **Payment Methods**: Credit card users have the lowest churn rate, while cash users have the highest churn rate.

## Recommendations
- Launch personalized coupon campaigns and loyalty programs to address churn among high-value customers.
- Improve website features across devices to reduce churn caused by device-related issues.
- Enhance customer retention strategies for new customers and offer targeted incentives.

## Tools Used
- Python
- Power BI
