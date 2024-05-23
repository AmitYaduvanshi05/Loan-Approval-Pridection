# Loan-Approval-Pridection

LOAN APPROVAL PREDICTION

MODEL

LOANS are the major requirement of the modern world. By this only, Banks get a major part of the total profit.
It is beneficial for students to manage their education and living expenses, and for people to buy any kind of luxury like houses, cars, etc.
But when it comes to deciding whether the applicant’s profile is relevant to be granted with loan or not. Banks have to look after many aspects.	
We are going to develop one such model that can predict whether a person will get his/her loan approved or not by using some of the background
information of the applicant like the applicant’s gender, marital status, income, etc.


Life Cycle Of ML Project

Data Collection : Gather relevant data for model training. This may include historical loan data, customer information, credit scores, 
employment history, and other relevant features. Ensure that the data is representative and diverse.
Download the dataset from here: Loan Prediction Problem Dataset (kaggle.com)
This dataset contains information about loan applications, including various attributes related to applicants and whether their loan 
applications were approved or denied. The dataset is designed for predictive modeling tasks, specifically for predicting whether a loan 
application will be approved or not based on the provided features.
The Dataset Contains 13 features
Let's discuss how each feature in the dataset could potentially impact the target feature,
which is "Loan_Status" (indicating whether the loan was approved or not).
Loan_ID: A unique identifier for each loan application. 
It doesn't contribute to the decision-making process but can be useful for record-keeping.

Gender:
Lending institutions might consider gender as a factor in loan approval, depending on historical data or institutional policies.
For instance, if there's evidence of gender-based discrimination, it could affect loan approval.

Married:
Married individuals may be perceived as more financially stable and responsible.
Lenders might be more inclined to approve loans for married applicants.

Dependents:
The number of dependents could influence loan approval, as more dependents might mean higher financial responsibilities. 
Lenders may assess the applicant's ability to repay the loan considering their family size.

Education:
The level of education might be a proxy for the applicant's earning potential and financial stability.
Graduates may be perceived as having better job prospects and, consequently, higher repayment capabilities.

Self_Employed:
Self-employed individuals may face different income patterns compared to salaried individuals.
Lenders might scrutinize the stability of self-employed applicants' income sources.

ApplicantIncome: Higher income generally indicates a better ability to repay a loan. However, extremely high or low incomes might be red flags.
Lenders may set income thresholds for loan approval.

CoapplicantIncome: The income of the coapplicant can supplement the household income, affecting the overall repayment capacity.
A higher coapplicant income may positively influence loan approval.

LoanAmount: The amount of the loan applied for is crucial.
Lenders will assess whether the requested loan amount aligns with the applicant's income and financial situation.

Loan_Amount_Term: The term of the loan affects monthly repayment amounts. Shorter terms might indicate a quicker repayment ability,
while longer terms might be associated with higher overall interest payments.

Credit_History: This is likely one of the most critical factors. A good credit history (1.0) is generally associated with a higher likelihood of loan approval.
Lenders heavily rely on credit history to assess risk.

Property_Area: The location of the property can influence loan approval. Urban areas might have different risk profiles than rural areas, 
and lenders may have specific criteria for different regions.


Data Cleaning : Clean the data to handle missing values, outliers, and inconsistencies. This step is crucial for the model's accuracy and generalization.
We may need to impute missing values, standardize or normalize features, and deal with any data anomalies.

Exploratory Data Analysis (EDA): Conduct exploratory data analysis to understand the relationships between different variables,
identify patterns, and gain insights. Visualization tools can be helpful in this phase.

Feature Engineering: Create new features or modify existing ones to improve the model's performance.
This might involve transforming variables, creating interaction terms, or encoding categorical variables.

Data Splitting: Split the dataset into training and testing sets. 
The training set is used to train the model, and the testing set is used to evaluate its performance.

Model Selection: Choose an appropriate machine learning algorithm for your problem.
Common algorithms for loan approval prediction include logistic regression, decision trees, random forests, and support vector machines.

Model Training: Train the selected model using the training dataset.
This involves feeding the algorithm the features and corresponding labels and letting it learn the patterns in the data.

Model Evaluation: Evaluate the model's performance on the testing dataset using appropriate metrics such as accuracy, precision, recall, and F1 score


