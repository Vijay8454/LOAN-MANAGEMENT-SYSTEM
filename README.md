Loan Management System :

•	Customer Grades: Set based on applicant income, helping to categorize customers for loan eligibility
•	Interest Calculation: Monthly and annual interest amounts are computed based on both income and property area type (rural, semi-rural, urban, semi-urban)
•	Automation with Triggers: Triggers were implemented to automatically update CIBIL scores and flag ineligible applicants at both row and statement levels
•	Data Cleaning: Involves filtering out unprocessed or rejected loans, and updating customer gender and age based on customer IDs
•	Stored Procedure and Final Dataset: A stored procedure was created to generate key outputs, such as filtering high CIBIL score customers and identifying 
                                      customer types (home office or corporate), after joining all five tables
