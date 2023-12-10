# German-Credit-Risk-Analysis

## Problem Statement
When evaluating loan applications, companies face the challenge of determining whether to approve or reject based on the applicant's credit risk.
Credit risk is the potential of a borrower to default on debt payments. <br>
There are two key risks involved: rejecting a good credit risk leads to a loss of business, while approving a bad credit risk results in financial losses for the company, including the principal amount. <br>
Effectively designing effective strategies for financial institutions to assess, predict, and manage the risk of borrower default. <br>

## Approach

***1. Scope Analysis: Exploration of Variables and Analysis of Redundancy*** :    <br>

In this phase, variables are explored and analyzed for redundancy within the dataset. The process involves retrieving German bank data, generating a variable list, removing irrelevant variables, creating essential Co-Variates, identifying expected relationships, assessing observed consistency, and eliminating variables without meaningful connections. This ensures a focused dataset, enhancing the effectiveness of credit risk assessment and other analytical tasks.
<br>

***2. Portfolio Review and Gap Identification*** :    <br>

In the subsequent stage, the complete portfolio undergoes measurement using diverse metrics on overall account data, balances, average balances, reporting total duration, and average loan duration. This process also involves the identification of any shortcomings or gaps present in the current strategy and flagging the concern to justify the Scorecard development. <br>

***3. Data Quality Checks*** :    <br>

In the next phases, Data Quality check are being performed. It involves classifying the variables into distinct categories, including identification, date, continuous, and categorical variables and Conduct a thorough examination of missing observations for all variables. The Key continuous variables are analyzed through univariate analysis, gaining insights into their individual distributions,parallelly key categorical variables is analyzed using frequency distribution offering a detailed examination of the occurrence of different categories within each variable. This systematic approach ensures a comprehensive exploration and understanding of the  bank dataset, covering data extraction, variable classification, handling missing data, and detailed analyses of both continuous and categorical variables.  <br>

***4. Data Preparation and Model Development*** :    <br>

In the concluding stage, the dataset is split into model development and Model Validation dataset. A model is constructed using the development data, and the resulting model equation is applied to the validation data. Neccessary measure taken  to have balanced bad rate distribution for Development and Validation Samples, statistical test is performed for model accuracy and stability and caution taken to avoid high multicollinearity.   <br>

## Data Insights 
1.  79% of the bad borrowers are concentrated in the category of borrowers who do not have any savings account or maintain low savings balances. Borrowers who maintained more than 100DM in their savings account balances contain only 16% of the overall bad borrowers <br>

2. The Current account which 'Have Current Account' Contain Relatively More Risky Borrower than Account with No Current Account. Hence, Check Account is a Potential Segmentation Variable. <br>

3. Non-Relationship Borrower resulted in 46% of the Defaults whereas Relationship Borrower resulted in 31% of the defaults in relationship segment. In total, Overall default was 42%. <br>

4. Nearly 80% of the total accounts in the portfolio are related to Automobiles and Consumption loans. These two products collectively contribute to almost 75% of the total bad accounts Hence, there is a chance that larger defaults may occur with significant exposures,especially in the case of large-ticket transactions. <br>

5. The majority of the accounts classified as bad are primarily associated with Auto loans and Consumption Loans. <br>

6. The average age of customers in the group which are Good is 36, whereas the average age in the group which turned into Bad Account is 33. <br>

7. Bad rates are noted in the 19-29 age group, while conversely, good rates are also observed in the same age group. Additionally, there is a decrease in bad rates from the 19-29 age group to the 59-69 age group, indicating a 
    continuous rank ordering without a significant break. <br>
    
8. One important observation across all job categories is that an employee becomes more reliable after working for more than four years in a given profession. Hence, the bad rate declines in the category employment = 3,4. <br>

9. German Bank has total Receivable of 3.2 Million Deutschmark and Average Receivable of 3271.2 Deutschmark. Bank total accounts reported was 1000 accounts. <br>

10. The average Loan Duration given to borrower turned bad is 2 Years however the average Loan Duration given to borrower not defaulted is 1 Year 7 Months. <br>

## Summary 

![Screenshot 2023-12-11 001030](https://github.com/ashwinjai/German-Credit-Risk-Analysis/assets/36980518/6bbd04a2-95e4-4a3f-931e-f58ab588ee0c)  <br>


![Screenshot 2023-12-11 001312](https://github.com/ashwinjai/German-Credit-Risk-Analysis/assets/36980518/6ac4d744-b2bb-4d60-8061-7a0c5ffe9e7e)  <br>











