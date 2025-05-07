# Consumer-Complaints-Dataset
## Introduction
This project analyzes consumer complaint data submitted to various financial institutions in the U.S. The goal is to identify key trends, performance metrics, and potential areas for service improvement based on consumer feedback.
## Dataset Overview
The dataset includes the following key columns:

- ID: Unique complaint identifier
- Company: Financial institution involved
- Product: Type of financial product (e.g., mortgage, credit reporting)
- Issue: Specific complaint issue
- State and State name: Location of the consumer
- Submitted via: Method of complaint submission (web, phone, mail, etc.)
- Date received / resolved
- Timely response?: Whether the company responded promptly
- Consumer disputed?
- Resolution time (in days): Time taken to resolve
- Year and Quarter

## Data Cleaning & Preparation
Steps taken:
- Parsed date fields (Date received, Date resolved) to datetime format
- Cleaned missing values, especially in fields like Resolution time
- Normalized categorical entries (e.g., 'Yes'/'No')

## Exploratory Data Analysis (EDA)
### Complaint Volume
- Total number of complaints
- Complaints per year and quarter
- Trend analysis over time
![Screenshot 2025-05-07 223449](https://github.com/user-attachments/assets/6d6b1fdc-8cf8-48d0-a0e2-3d56aaa5daff)

### Top Complaint Categories
- Most common products with complaints
- Frequent issues reported
- Distribution by submission channel
### Company Performance
- Companies with highest complaint volumes
- Timely response rates per company
- Average resolution time by company
### Geographic Analysis
- States with highest complaint volumes
- State-wise resolution efficiency
### Dispute and Timeliness
- Percentage of complaints marked as "Consumer disputed"
- Correlation between disputed complaints and resolution time

## Key Insights
- Identification of systemic issues in specific products or companies
- Observations about delays in resolution and their impact
- Regional patterns in complaint types and volume

## Dashboard Review
![Screenshot 2025-05-07 165510](https://github.com/user-attachments/assets/4d92dfcc-3af2-44c8-8e5e-36bd4f759051)

## Recommendations
- Improve response times in underperforming companies
- Focus on most disputed product areas for quality review
- Encourage user-friendly digital complaint submission platforms

## Conclusion
  The complaint data provides a rich source for performance benchmarking, customer sentiment tracking, and quality improvement in the financial services industry.
