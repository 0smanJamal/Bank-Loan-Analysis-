# Bank Loan Analysis
# Project Overview
This project involves a detailed analysis of bank loan data using SQL for planning and analysis, and Power BI for visualization. The Power BI dashboard offers a comprehensive view of loan metrics, including total applications, funded amounts, interest rates, and more. It also provides insights into loan quality, status, and regional trends.

Here's the updated README for your bank loan analysis project, incorporating the details you provided:

# Technologies Used
SQL: For data extraction, transformation, and analysis.
Power BI: For data visualization and dashboard creation.

# SQL Planning and Analysis
The SQL analysis involved:

Total Loan Applications: Calculated the total number of loan applications received during a specified period. Monitored Month-to-Date (MTD) applications and tracked Month-over-Month (MoM) changes.
Total Funded Amount: Determined the total amount of funds disbursed as loans. Analyzed MTD funded amounts and MoM variations.
Total Amount Received: Tracked the total amount received from borrowers, including MTD and MoM changes.
Average Interest Rate: Calculated the average interest rate across all loans and monitored MTD and MoM fluctuations.
Average Debt-to-Income Ratio (DTI): Evaluated the average DTI for borrowers, including MTD and MoM changes.
Good Loan vs. Bad Loan KPIs
Good Loan KPIs:

Good Loan Application Percentage: Percentage of applications classified as 'Good Loans' (status 'Fully Paid' and 'Current').
Good Loan Applications: Total number of 'Good Loan' applications.
Good Loan Funded Amount: Total amount disbursed as 'Good Loans'.
Good Loan Total Received Amount: Total amount received from borrowers for 'Good Loans'.
Bad Loan KPIs:

Bad Loan Application Percentage: Percentage of applications categorized as 'Bad Loans' (status 'Charged Off').
Bad Loan Applications: Total number of 'Bad Loan' applications.
Bad Loan Funded Amount: Total amount disbursed as 'Bad Loans'.
Bad Loan Total Received Amount: Total amount received from borrowers for 'Bad Loans'.
Loan Status Grid View
Created a grid view report categorized by 'Loan Status,' including metrics such as:

Total Loan Applications
Total Funded Amount
Total Amount Received
MTD Funded Amount
MTD Amount Received
Average Interest Rate
Average DTI
# Power BI Dashboard
The Power BI dashboard is divided into three main pages:

Summary Page
The Summary Page provides a high-level overview of key loan metrics, including:

Total Loan Applications: Card visual displaying the total number of loan applications.
Total Funded Amount: Card visual showing the total amount disbursed as loans.
Total Amount Received: Card visual indicating the total amount received from borrowers.
Average Interest Rate: Card visual showing the average interest rate.
Average Debt-to-Income Ratio (DTI): Card visual presenting the average DTI.
Key Performance Indicators (KPIs): Summary of critical metrics.
Overview Page
The Overview Page visualizes critical loan-related metrics and trends through various charts:

Monthly Trends by Issue Date (Line Chart): Shows trends in 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received' over time.
Loan Term Analysis (Donut Chart): Depicts loan statistics based on different loan terms (e.g., 36 months, 60 months).
Employee Length Analysis (Bar Chart): Illustrates lending metrics based on borrowers' employment lengths.
Loan Purpose Breakdown (Bar Chart): Provides a visual breakdown of loan metrics by loan purpose.
Home Ownership Analysis (Tree Map): Shows loan metrics categorized by home ownership status.
Details Page
The Details Page offers a comprehensive view of all loan-related data:

Customer Details: Detailed tables listing all customer information.
Loan Details: Comprehensive tables with detailed loan information.
Loan Metrics by State and Term: Detailed breakdowns of loan metrics by state and term.
