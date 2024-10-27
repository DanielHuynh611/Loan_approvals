
## Dataset

The dataset includes diverse features such as demographic information, credit history, employment status, income levels, existing debt, and other relevant financial metrics. The primary objective is to train classification models to determine the outcome of loan approval.

### Columns

| Column                     | Meaning                          |
|----------------------------|----------------------------------|
| ApplicationDate            | Loan application date            |
| Age                        | Applicant's age                  |
| AnnualIncome               | Yearly income                    |
| CreditScore                | Creditworthiness score           |
| EmploymentStatus           | Job situation                    |
| EducationLevel             | Highest education attained       |
| Experience                 | Work experience                  |
| LoanAmount                 | Requested loan size              |
| LoanDuration               | Loan repayment period            |
| MaritalStatus              | Applicant's marital state        |
| NumberOfDependents         | Number of dependents             |
| HomeOwnershipStatus        | Homeownership type               |
| MonthlyDebtPayments        | Monthly debt obligations         |
| CreditCardUtilizationRate  | Credit card usage percentage     |
| NumberOfOpenCreditLines    | Active credit lines              |
| NumberOfCreditInquiries    | Credit checks count              |
| DebtToIncomeRatio          | Debt to income proportion        |
| BankruptcyHistory          | Bankruptcy records               |
| LoanPurpose                | Reason for loan                  |
| PreviousLoanDefaults       | Prior loan defaults              |
| PaymentHistory             | Past payment behavior            |
| LengthOfCreditHistory      | Credit history duration          |
| SavingsAccountBalance      | Savings account amount           |

## Project Workflow

The project follows the CRISP-DM (Cross Industry Standard Process for Data Mining) framework, which includes the following phases:

1. **Business Understanding**: Clarify project objectives and requirements from a business perspective.
2. **Data Understanding**: Initial data collection and exploration to identify data quality issues and uncover preliminary insights.
3. **Data Preparation**: Build the final dataset from the original raw data, including handling missing values, encoding categorical variables and rescaling.
4. **Modeling**: Choose and implement different modeling techniques, adjusting parameters to achieve optimal values.
5. **Evaluation**: Thoroughly evaluate the model's performance to ensure its effectiveness and reliability.
6. **Deployment**: Deploy the highest-performing model for practical use.

## Usage

1. **Install Dependencies**: Ensure you have all the required dependencies by running:
    ```sh
    pip install -r requirements.txt
    ```

2. **Run the Notebook**: Open and run the [Loan_approval_prediction.ipynb](Loan_approval_prediction.ipynb) notebook to execute the data analysis and model training steps.

## Results

By performing a comparative experiment with three classification models (Logistic Regression, k-Nearest Neighbors, and Gaussian Naive Bayes), combined with hyperparameters tuning to optimize models' performance, the highest-performing model is the Logistic Regression model trained with 22 out of 49 features. This model achieved an accuracy score of 0.97 and an F1 score of 0.94.

## Business Implications

The results of this loan approval prediction project have several important business implications for organizations involved in risk assessment and loan approval processes:

1. **Improved Decision-Making Efficiency**: The Logistic Regression model, achieving an accuracy of 97%, demonstrates its ability to effectively predict loan approval outcomes. By automating the decision-making process, organizations can significantly reduce the time and effort required to assess loan applications, allowing for faster approvals and better resource allocation.
2. **Improved Risk Management**: The model's accuracy in detecting high-risk applicants enables financial institutions to minimize potential loan defaults. By leveraging predictive insights, lenders can enhance their risk assessment strategies, leading to more informed decisions and reduced default rates.
## License

This project is licensed under the MIT License.
