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
