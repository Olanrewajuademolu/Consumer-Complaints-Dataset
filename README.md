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
![Screenshot 2025-05-08 003658](https://github.com/user-attachments/assets/789afdae-da32-43b3-9d15-abf8a78b8bb9)


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
![Screenshot 2025-05-07 223449](https://github.com/user-attachments/assets/cf06a8ad-7ce2-483b-a59f-4d01389cab5b)

### Top Complaint Categories
- Most common products with complaints
- Frequent issues reported
- Distribution by submission channel
![Screenshot 2025-05-08 001010](https://github.com/user-attachments/assets/d144eae8-6403-4525-86e9-477f435d4aee)

### Company Performance
- Companies with highest complaint volumes
- Timely response rates per company
- Average resolution time by company
![Screenshot 2025-05-08 110414](https://github.com/user-attachments/assets/dc3b99e9-b025-445a-8512-baad370c74c5)

### Geographic Analysis
- States with highest complaint volumes
- State-wise resolution efficiency
![Screenshot 2025-05-08 110703](https://github.com/user-attachments/assets/fc60b604-d0c5-405c-abda-4b7dde5bbca6)

### Dispute and Timeliness
- Percentage of complaints marked as "Consumer disputed"
- Correlation between disputed complaints and resolution time
![Screenshot 2025-05-08 123324](https://github.com/user-attachments/assets/d7c5efcf-119e-4faa-925b-787866728775)
![Screenshot 2025-05-08 135547](https://github.com/user-attachments/assets/cbb1b4e3-6fce-4520-9803-0adee1bb7a22)

## Key Insights
- Identification of systemic issues in specific products or companies
- Observations about delays in resolution and their impact
- Regional patterns in complaint types and volume

## Dashboard Review
# ![Screenshot 2025-05-07 165510](https://github.com/user-attachments/assets/4d92dfcc-3af2-44c8-8e5e-36bd4f759051)

## Recommendations
- Improve response times in underperforming companies
- Focus on most disputed product areas for quality review
- Encourage user-friendly digital complaint submission platforms

## Conclusion
  The complaint data provides a rich source for performance benchmarking, customer sentiment tracking, and quality improvement in the financial services industry.
