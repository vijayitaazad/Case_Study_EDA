# Leading Club Case Study

## Problem Statement
The consumer finance company focuses on lending to urban customers while managing two main risks in loan approvals:

- **Loss of Business Risk**: Not approving loans for applicants likely to repay results in lost opportunities.
- **Financial Loss Risk**: Approving loans for applicants likely to default can lead to significant financial losses.

The goal is to analyze historical loan applicant data to identify patterns indicating the likelihood of default, helping the company make informed lending decisions.

## Objective
Develop a comprehensive understanding of the factors driving loan defaults to improve risk assessment and portfolio management.

## Data Source
- **Dataset**: `loan.csv`
- **Data Dictionary**: Provides detailed information about each column.

## Data Cleaning Steps
1. **Handling Missing Values**: Identify and impute missing values or drop excessive missing data.
2. **Removing Duplicates**: Check and eliminate duplicate entries.
3. **Data Type Conversion**: Ensure correct data types (e.g., convert terms to numerical formats).
4. **Outlier Detection and Treatment**: Identify and handle outliers using statistical methods.
5. **Feature Engineering**: Bin continuous variables for better analysis.
6. **Count Values**: Identify and eliminate columns with unique values that offer no analytical value.

## Univariate Analysis
- **Focus**: Analyze one variable at a time to understand distribution, central tendency, and variability.

### Key Findings:
- **Credit Grade**: Applicants with a grade of 'B' and sub-grade 'B5' are more likely to default.
- **Interest Rate**: Higher likelihood of default is observed between 10% and 17%.
- **Annual Income**: Default risk increases for incomes between $40,000 and $60,000.
- **Loan Purpose**: Debt consolidation is a common reason for defaults.

## Bivariate Analysis
- **Focus**: Examine relationships between two variables.

### Key Insights:
- **Credit Grades**: Lower grades (B, C, D) correlate with higher default rates.
- **Geographic Factors**: States like CA, FL, and NJ show higher default rates.
- **Income Level**: Lower incomes correlate with higher default rates.
- **Loan Amount and Purpose**: Larger loans and specific purposes (e.g., debt consolidation) are linked to increased risk.

## Multivariate Analysis
- **Interactions**: Analyze how multiple variables influence loan defaults.

### Findings:
- **Positive Correlations**: Loan amount and installment payments, annual income and loan amount.
- **Weak Correlation**: Debt-to-Income (DTI) shows minimal correlation with other variables.
- **Negative Correlation**: DTI decreases as income increases.

## Recommendations
1. **Enhanced Risk Assessment Models**: Implement advanced algorithms considering multiple risk factors.
2. **Targeted Financial Education Programs**: Offer resources for lower-income borrowers to improve repayment strategies.
3. **Geographic Risk Strategies**: Adjust lending practices based on regional default trends.
4. **Housing Stability Initiatives**: Support programs for renters and mortgaged homeowners.
5. **Custom Loan Products**: Create flexible loan products tailored to different borrower needs.
6. **Incentives for Responsible Borrowing**: Encourage responsible financial behavior with rewards.

This analysis serves as a foundation for improving lending practices and reducing default risks.
