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




