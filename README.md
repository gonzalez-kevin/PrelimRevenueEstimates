# PrelmRevenueEstimates
Estimate Revenue amounts per account based on start and end dates of service for customers.

**Here are the questions I was interested in asking:**
1. Can revenue by account for the month be forecasted to determine services that require more attention?

**I took the following steps to complete my analysis:**
1. Pulled in the data via a CSV file and created a Common Table Expression to focus on pertinent fields
2. Generated a SQL query to determine billable amount for the month for each customer based prorated based on service start and end dates
3. Ran a Python script on the resulting table from the SQL query to group billable amount by each revenue account and exported to an Excel file to present as a report

**Here are my key takeaways:**
1. Using a combination of a SQL query to perform calculations and using a Python script on the resulting table was the best way to present the requested information to key stakeholders
