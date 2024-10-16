# Risk-Analytics-with-Python
## Problem Statement:
- Developing a basic understanding of risk analytics in banking and financial services and understand how data is used to minimize the risk of losing money while lending to customers.
## Project Objectives: 
- Examining the impact of variables such as loan type, loan purpose, business or commercial nature, and credit score on loan defaults.
- Investigating the correlation between upfront charges, loan amount, interest rates, and property values with the likelihood of default. -
- Analyzing patterns and uncovering insights into default tendencies.

## Data Description

| Column Name               | Description                                                                                                  |
|---------------------------|--------------------------------------------------------------------------------------------------------------|
| **ID**                     | Unique identifier for each row                                                                               |
| **year**                   | Year when the loan was taken                                                                                 |
| **loan_limit**             | Indicates if the loan limit is fixed or variable: `cf` - confirm/fixed, `ncf` - not confirm/not fixed        |
| **Gender**                 | Gender of the applicant: `male`, `female`, `not specified`, `joint` (in case of applying as a couple)        |
| **loan_type**              | Type of loan (masked data): `type-1`, `type-2`, `type-3`                                                     |
| **loan_purpose**           | Purpose of the loan (masked data): `p1`, `p2`, `p3`, `p4`                                                    |
| **business_or_commercial** | Specifies if the loan is for a commercial establishment or personal establishment                            |
| **loan_amount**            | Amount of the loan                                                                                           |
| **rate_of_interest**       | Interest rate applied to the loan                                                                            |
| **Upfront_charges**        | Down payment made by the applicant                                                                           |
| **property_value**         | Value of the property for which the loan is taken                                                            |
| **occupancy_type**         | Occupancy type for the establishment                                                                         |
| **income**                 | Income of the applicant                                                                                      |
| **credit_type**            | Credit type of the applicant: `EXP`, `EQUI`, `CRIF`, `CIB`                                                   |
| **Credit_Score**           | Credit score of the applicant                                                                                |
| **co-applicant_credit_type** | Credit type of the co-applicant                                                                             |
| **age**                    | Age of the applicant                                                                                         |
| **LTV**                    | Loan-to-value ratio of the applicant                                                                         |
| **Region**                 | Region of the applicant                                                                                      |
| **Status**                 | Loan status: `1` - defaulter, `0` - normal                                                                   |

## Methodology
- Data loading and exploaration
- Data cleaning
- Feature Enginnering
- Univariate Analysis
- Bivariate Analysis
- Multivariae Analysis
- Impact of ddifferent variabes on defaulters
- Insights
- Key Findings
- Recommendations

## Colab Notebook
- You can access the full Python analysis on Google Colab using the following link: [View the notebook](https://colab.research.google.com/drive/1li2QhpJ6fHJhvOSWXPBEfSAB8A7rD-S7#scrollTo=UUqOHrjdpfx0)
