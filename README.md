## Marketing Funnel & Conversion Performance Analysis

## Project Overview

This project focuses on analyzing bank marketing campaign performance to understand customer subscription behavior, evaluate campaign engagement, and identify patterns associated with successful subscriptions.

The project was completed as part of the **Future Interns Data Science & Analytics Internship — Task 3** using Python, Excel, and Power BI.

The analysis uses the UCI Bank Marketing dataset to explore subscription outcomes, customer characteristics, contact methods, and previous campaign performance.

## Objectives

- Analyze overall marketing campaign outcomes.
- Calculate subscription and non-subscription rates.
- Identify customer groups with different subscription patterns.
- Examine campaign engagement through call duration and contact frequency.
- Compare campaign outcomes across customer characteristics and contact methods.
- Develop actionable recommendations to support marketing decisions.

## Tools and Technologies

- **Python:** Data analysis and exploratory data analysis
- **Pandas and NumPy:** Data cleaning and manipulation
- **Matplotlib and Seaborn:** Data visualization
- **Jupyter Notebook:** Analysis and documentation
- **Microsoft Excel:** Data cleaning and preparation
- **Microsoft Power BI:** Interactive dashboard and KPI visualization
- **GitHub:** Project version control and documentation

## Dataset

The project uses the **Bank Marketing dataset** from the UCI Machine Learning Repository.

The dataset contains customer demographic information, contact details, campaign activity, previous campaign outcomes, and the final subscription status.

The target variable indicates whether a customer subscribed to a term deposit (`yes` or `no`).

Dataset source: https://archive.ics.uci.edu/dataset/222/bank+marketing

**Note:** This project analyzes bank marketing campaign conversion outcomes. It does not represent a website visitor-to-purchase funnel.

## Data Cleaning and Preparation

The dataset was cleaned and prepared using Microsoft Excel and Python.

The preparation process included:

- Reviewing column names and data types.
- Improving column names for readability.
- Checking missing, unknown, zero, and negative values.
- Reviewing categorical variables such as job role, education level, contact method, and previous campaign outcome.
- Preparing the cleaned dataset for exploratory analysis and Power BI visualization.

Unknown and special values were interpreted according to their meaning in the dataset rather than automatically removed.

## Key Performance Indicators

The analysis covers 45,211 campaign records.

| Metric | Value |
|---|---:|
| Total Campaign Records | 45,211 |
| Successful Subscriptions | 5,289 |
| Unsuccessful Subscriptions | 39,922 |
| Subscription Rate | 11.70% |
| Non-Subscription Rate | 88.30% |

## Exploratory Data Analysis Using Python

Python was used to examine subscription patterns across different customer and campaign attributes.

The analysis included:

- Subscription outcome distribution.
- Subscription rate by job role.
- Subscription rate by contact method.
- Subscription rate by previous campaign outcome.
- Subscription rate by education level.
- Summary tables comparing total records, successful subscriptions, and subscription rates.

## Power BI Dashboard

The interactive Power BI dashboard contains three pages.

### Page 1: Campaign Overview

This page presents the overall performance of the marketing campaign.

Key visuals include:

- Total Campaign Records.
- Successful Subscriptions.
- Subscription Rate.
- Non-Subscription Rate.
- Subscription Outcomes.
- Subscription Rate by Job Role.

### Page 2: Conversion Drivers

This page compares subscription outcomes across customer characteristics and campaign-related categories.

Key visuals include:

- Subscription Rate by Contact Method.
- Subscription Rate by Education Level.
- Subscription Rate by Previous Campaign Outcome.
- Subscription Rate by Marital Status.

### Page 3: Campaign Engagement

This page explores campaign activity and contact patterns without using conversion rate as the chart metric.

Key visuals include:

- Average Call Duration by Subscription Status.
- Average Current Campaign Contacts by Subscription Status.
- Campaign Records by Contact Method.
- Records by Previous Campaign Outcome.


## Key Findings

- The overall subscription rate was 11.70% across the analyzed campaign records.
- Subscription rates varied across job roles and customer characteristics.
- Customers with a successful previous campaign outcome showed a higher observed subscription rate than other previous-outcome groups.
- Contact method and education level showed differences in subscription patterns.
- Call duration and contact frequency provided additional context for understanding campaign engagement.

These findings describe observed associations in the dataset and should not be interpreted as proof of causation.

## Business Recommendations

- Investigate the approaches used in previously successful campaigns.
- Test tailored communication strategies for customer groups with different subscription patterns.
- Review contact frequency to understand how repeated outreach relates to campaign outcomes.
- Evaluate campaign engagement metrics alongside subscription results.
- Monitor future campaign performance to determine whether changes improve subscription outcomes.

## Project Structure

```text
FUTURE_DS_03/
│
├── README.md
├── bank_marketing_cleaned.csv
├── Bank_Marketing_Analysis.ipynb
├── Bank_Marketing_Conversion_Analysis.pbix
│
└── screenshots/
    ├── campaign-overview.png
    ├── conversion-drivers.png
    └── campaign-engagement.png
```

## How to Run the Project

### Python Analysis

1. Clone or download the repository.
2. Install the required Python libraries if they are not already installed.
3. Open `Bank_Marketing_Analysis.ipynb` in Jupyter Notebook or Google Colab.
4. Update the dataset path if necessary.
5. Run the notebook cells to review the analysis and visualizations.

### Power BI Dashboard

1. Open `Bank_Marketing_Conversion_Analysis.pbix` in Power BI Desktop.
2. If prompted, reconnect the report to `bank_marketing_cleaned.csv`.
3. Explore the dashboard pages and visualizations.

## Conclusion

This project demonstrates how data cleaning, exploratory analysis, and interactive visualization can be combined to evaluate bank marketing campaign performance.

By analyzing subscription outcomes, customer characteristics, and campaign engagement, the project provides insights that can help inform future marketing strategies.

## Author

**Jaden Fernandes**

## Acknowledgements

- Future Interns — Data Science & Analytics Internship
- UCI Machine Learning Repository — Bank Marketing dataset
