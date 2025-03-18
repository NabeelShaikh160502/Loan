# Loan

## Loan datasets can be quite detailed, depending on their source and purpose. Below is a deeper breakdown of typical fields found in loan datasets, categorized for credit risk modeling, loan approvals, and financial analysis.

### 1. Borrower Demographics
Includes personal information about the borrower, useful for assessing credit risk and understanding borrower behavior.

Feature	Description
Applicant ID	Unique identifier for the borrower.
Full Name	Borrower's name (may be anonymized in public datasets).
Age	Borrower's age in years.
Gender	Male/Female/Other.
Marital Status	Single/Married/Divorced/Widowed.
Dependents	Number of dependents (spouse, children, parents).
Education Level	High School/Graduate/Postgraduate/Doctorate.
Employment Type	Salaried, Self-employed, Business owner, Retired, Unemployed.
Occupation	Industry and job title (IT, Banking, Healthcare, etc.).
Work Experience	Number of years in the current job.
Residential Status	Own/Rented/Company-provided/Family house.

### 2. Financial & Credit History
These features help in assessing the borrower’s creditworthiness.

Feature	Description
Monthly Income	Borrower's salary or business income.
Co-Applicant Income	Income of co-applicant (spouse, parents, etc.).
Household Expenses	Monthly expenses for food, rent, bills, etc.
Existing Debts	Total outstanding loans (home loan, credit card, etc.).
Debt-to-Income Ratio (DTI)	Percentage of income spent on debt repayments.
Credit Score	Borrower’s creditworthiness score (e.g., CIBIL, Experian).
Number of Credit Cards	Total active credit cards.
Average Credit Card Utilization (%)	Percentage of total credit limit used.
Previous Loan Defaults	Number of times the borrower defaulted on previous loans.
Loan Application History	Total number of loan applications made.

### 3. Loan Application Details
These fields describe the loan being requested.

Feature	Description
Loan ID	Unique identifier for the loan.
Loan Type	Home Loan, Auto Loan, Personal Loan, Business Loan, etc.
Loan Amount	Amount requested by the borrower.
Approved Loan Amount	Amount sanctioned by the lender.
Loan Term (Tenure)	Duration of the loan in months/years.
Loan Purpose	Education, Medical, Home Renovation, Debt Consolidation, etc.
Interest Rate (%)	Annual percentage rate (APR) on the loan.
Processing Fee	Fee charged for loan processing.
Loan Collateral	Asset used as security (property, gold, car, etc.).

### 4. Loan Repayment Details
These features capture borrower repayment behavior.

Feature	Description
EMI (Equated Monthly Installment)	Fixed monthly repayment amount.
First EMI Date	Date of the first EMI payment.
Number of Missed Payments	Total number of missed EMIs.
Number of Late Payments	Total number of delayed EMIs.
Loan Prepayment	Whether the borrower has repaid the loan early.
Outstanding Balance	Remaining loan amount to be paid.
Penalty Charges	Fees charged for late or missed payments.
Final Loan Status	Fully Paid, Ongoing, Defaulted, Closed.

### 5. Property & Collateral Details (For Secured Loans)
Applicable to home loans, car loans, and loans backed by collateral.

Feature	Description
Property ID	Unique identifier for the property.
Property Type	Apartment, Independent House, Villa, Commercial.
Property Location	City, State, ZIP code of the property.
Property Value	Market value of the property.
Loan-to-Value (LTV) Ratio	Loan amount as a percentage of property value.
Ownership Status	Single owner, Joint ownership, Inherited property.
Car Model (for Auto Loans)	Make, model, and year of the vehicle.
Insurance Coverage	Whether the collateral (house/car) is insured.

### 6. Additional Features for Risk Analysis
Advanced features used in machine learning models for credit risk assessment.

Feature	Description
Fraud Flags	Indicator for potential fraud cases.
Bureau Score History	Historical credit scores over time.
Employment Stability	Years in current job or business.
Customer Relationship Length	Number of years as a customer of the bank.
Number of Active Loans	Total ongoing loans (home, personal, credit card, etc.).
Mode of Repayment	Auto-debit, Cheque, Online Transfer, Cash.
Change in Income Level	Increase/decrease in income over time.
Loan Restructuring	Whether the loan was modified due to financial distress.

### 7. Derived Features for ML Models
If you're using AI/ML for credit scoring or risk assessment, you might derive additional features:

Derived Feature	Description
Credit Utilization Ratio	(Total Debt / Total Credit Limit) * 100
Installment-to-Income Ratio	(Monthly EMI / Monthly Income) * 100
Payment History Score	Weighted score based on past payment behavior.
Risk Category	Low, Medium, High-risk borrower based on ML predictions.
