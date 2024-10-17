
# **Automated USA Financial Data Analysis**

## Project Overview
This project automates the process of financial data analysis to make it faster and more efficient. The goal is to handle 25 files daily from different regions and create a report by 8 PM.

## Dashboard Link
https://app.powerbi.com/view?r=eyJrIjoiZmY2ZWNmNzgtNTJkYS00NjMzLWE2YTktN2FiMTVmMjAxM2QxIiwidCI6IjYwY2M1ZGI0LTRjZTEtNDEwNS1iY2RlLWJjMjY0NmI2NDMyNyJ9

## Problem Statement
Manually sorting, cleaning, transforming, and reporting 25 files every day by 8 PM was inefficient.

## Solution
### To fix this, I automated the entire workflow. Here's how:

Steps Followed:
* Data Collection:

    Used Outlook to gather daily financial data into one folder.

* File Storage:

    Stored the files in Google Drive.

* API Development:

    Used Google Cloud Platform to create an API.

    Connected the Google Drive folder and Power BI using a Python script.

* Data Cleaning and Transformation:

    Cleaned and transformed the data in Power Query.

* Report Generation:

    Created visualizations in Power BI Desktop, including:

        Cards: Average annual income, average monthly balance, average number of payment delays, average credit utilization.

        Charts: Age trends in credit limit adjustment, credit scores across age groups, payment behavior by credit mix, loan distribution, potential customers by LTV score, customer age demographics, and more.

## Automated Report Delivery:

Set up an automated process to send the report to clients by 8 PM daily.




## Insights
This project provided several key insights:

### Customer Satisfaction:

    57% of customers are neutral or unsatisfied, while 43% are satisfied.

### Key Metrics:

    Average Annual Income: 166.99K

    Average Monthly Balance: 396.28

    Average Number of Delays in Payment: 21.24

    Average Credit Utilization: 32.25%

### Age-Related Trends in Credit Limit Adjustments:

The average of changed credit limits across different ages shows fluctuations:

    Age 14: 11.6

    Age 20: 10.3

    Age 30: 9.3

    Age 40: 11.7

    Age 45: 10.5

    Age 50: 7.6

    Age 60: 7.5

### Credit Scores Across Age Groups:

Average credit inquiries for different age groups:

    Teen: 8.4

    Young Adult: 6.9

    Old Adult: 6.9

    Old1: 6.8

    Old2: 4.4

### Payment Behavior Trends by Credit Mix:

Payment behavior across different credit mixes:

* Standard:

    High spent, Large value payments: 848

    High spent, Medium value payments: 1142

    High spent, Small value payments: 774

    Low spent, Large value payments: 724

    Low spent, Medium value payments: 882

    Low spent, Small value payments: 477

* Good:

    High spent, Large value payments: 776

    High spent, Medium value payments: 821

    High spent, Small value payments: 476

    Low spent, Large value payments: 478

    Low spent, Medium value payments: 970

    Low spent, Small value payments: 595

Missing Data: 356

* Above Standard:

    High spent, Large value payments: 506

    High spent, Medium value payments: 612

    High spent, Small value payments: 369

    Low spent, Large value payments: 387

    Low spent, Medium value payments: 501

    Low spent, Small value payments: 234

* Bad:

    High spent, Large value payments: 561

    High spent, Medium value payments: 314

    High spent, Small value payments: 401

    Low spent, Large value payments: 374

    Low spent, Medium value payments: 477

    Low spent, Small value payments: 270

Missing Data: 1092

## Demographic Insights:

    Most customers are from the '25-50' age group (52.44%)

    Majority of customers travel for business (69.06%)

# **Conclusion**
This project shows how automation can make data workflows faster and more accurate. It reduced manual work and improved reporting efficiency.

    Feel free to explore the dashboard and connect for more information!
