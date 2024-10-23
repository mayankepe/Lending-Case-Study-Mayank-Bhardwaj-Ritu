# Lending Club Case Study

Lending Club, a finance marketplace that provides a range of loans to urban customers, is facing a significant challenge in refining its loan approval process. The company needs to make informed decisions when evaluating loan applications to reduce financial losses, especially from borrowers who pose a higher risk of defaulting.

These financial losses, known as credit losses, happen when borrowers are unable to repay their loans. In simpler terms, when borrowers are "charged off," they create the largest financial strain on the company.

The main aim of this case study is to help Lending Club reduce these credit losses. The issue arises from two key scenarios:

### Recognizing Reliable Borrowers
Identifying applicants who are likely to repay their loans is vital since they contribute to the company's profits through interest payments. Missing out on these applicants could lead to lost revenue.

### Mitigating Risk of Default
On the other hand, approving loans for applicants who are unlikely to repay leads to significant financial losses.

## Contents
- [General Information](#general-information)
- [Key Findings](#key-findings)
- [Tools Used](#tools-used)
- [Acknowledgements](#acknowledgements)
- [Contributors](#contributors)

## General Information

### Objective
The goal is to identify applicants who are at risk of defaulting on their loans, helping to reduce overall credit losses. This case study aims to achieve this through exploratory data analysis (EDA) of the available data.

The company seeks to understand the factors that contribute to loan defaults, such as variables that serve as strong indicators of default risk. With this knowledge, the company can improve its portfolio management and risk assessment strategies.

## Key Findings
- **Risk in Grades B, C, and D**: Loan applicants from these grades are responsible for most of the "Charged Off" loans, so it would be prudent for the company to enforce stricter risk assessments for these applicants.
- **Focus on Subgrades B3, B4, and B5**: Applicants in these specific subgrades tend to have a higher chance of defaulting. The company may want to introduce additional measures to mitigate this risk or offer lower loan amounts to these individuals.
- **Loan Term Length**: Borrowers who take out 60-month loans are more likely to default, so the company might want to reconsider offering long-term loans or adjust interest rates for such applicants.
- **Experience and Default Risk**: Surprisingly, borrowers with more than ten years of experience show a higher likelihood of defaulting, suggesting that experience is not a reliable measure of creditworthiness. A more holistic scoring model that includes additional risk factors would be beneficial.
- **Market Growth**: The increasing number of loan applicants from 2007 to 2011 indicates steady growth. Lending Club can capitalize on this trend while ensuring its risk management processes stay strong.
- **Seasonal Loan Demand**: Loan applications peak in December and the fourth quarter, likely due to the holiday season. The company should prepare for higher demand during this time to ensure smooth processing.
- **Debt Consolidation Risk**: Since loans for debt consolidation make up a significant portion of defaults, the company should carefully evaluate applicants in this category, potentially adjusting rates or offering financial counselling.
- **Housing and Default Risk**: Applicants living in rented or mortgaged homes tend to default more often. This should be considered during the underwriting process, as housing stability impacts repayment ability.
- **Verification Concerns**: Verified applicants are defaulting at a higher rate than non-verified ones. The company should review its verification methods to ensure they are effective and make adjustments where necessary.
- **Geographical Risk**: Borrowers from states like California, Florida, and New York show higher default rates. The company should keep an eye on regional risks and adjust its lending policies for these areas accordingly.
- **High Loan Amounts**: Loans of $15,000 or more are more likely to default. To address this, Lending Club should implement more thorough evaluations for larger loan amounts and possibly limit loan sizes for riskier applicants.
- **Debt-to-Income (DTI) and Interest Rates**: Higher DTI ratios and interest rates between 13% and 17% are linked to defaults. The company should reassess how it sets interest rates, perhaps considering DTI ratios to align repayment ability with loan conditions.
- **Low Annual Income**: Applicants with incomes below $40,000 are at higher risk of defaulting. Offering financial education or limiting loan amounts based on income could help mitigate this risk.

## Tools Used
- **Python** 3.13
- **Matplotlib** 3.7.1
- **Numpy** 1.24.3
- **Pandas** 1.5.3
- **Seaborn** 0.12.2

## Acknowledgements
This project was inspired by a live session on Exploratory Data Analysis (EDA) conducted by Akash from upGrad.

## Contributors
Developed by @mayankepe
