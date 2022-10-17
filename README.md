# Classification -- Predicting Customer Churn

## Introduction

Customer attrition is one of the biggest expenditures of any
organization. Customer churn otherwise known as customer attrition or
customer turnover is the percentage of customers that stopped using your
company\'s product or service within a specified timeframe.\
For instance, if you began the year with 500 customers but later ended
with 480 customers, the percentage of customers that left would be 4%.
If we could figure out why a customer leaves and when they leave with
reasonable accuracy, it would immensely help the organization to
strategize their retention initiatives manifold.

In this project, we aim to find the likelihood of a customer leaving the
organization, the key indicators of churn as well as the retention
strategies that can be implemented to avert this problem.

## Data Understanding

The data for this project is in a csv format. The following describes
the columns present in the data.

**Gender** -- Whether the customer is a male or a female

**SeniorCitizen** -- Whether a customer is a senior citizen or not

**Partner** -- Whether the customer has a partner or not (Yes, No)

**Dependents** -- Whether the customer has dependents or not (Yes, No)

**Tenure** -- Number of months the customer has stayed with the company

**Phone Service** -- Whether the customer has a phone service or not
(Yes, No)

**MultipleLines** -- Whether the customer has multiple lines or not

**InternetService** -- Customer's internet service provider (DSL, Fiber
Optic, No)

**OnlineSecurity** -- Whether the customer has online security or not
(Yes, No, No Internet)

**OnlineBackup** -- Whether the customer has online backup or not (Yes,
No, No Internet)

**DeviceProtection** -- Whether the customer has device protection or
not (Yes, No, No internet service)

**TechSupport** -- Whether the customer has tech support or not (Yes,
No, No internet)

**StreamingTV** -- Whether the customer has streaming TV or not (Yes,
No, No internet service)

**StreamingMovies** -- Whether the customer has streaming movies or not
(Yes, No, No Internet service)

**Contract** -- The contract term of the customer (Month-to-Month, One
year, Two year)

**PaperlessBilling** -- Whether the customer has paperless billing or
not (Yes, No)

**Payment Method** -- The customer's payment method (Electronic check,
mailed check, Bank transfer(automatic), Credit card(automatic))

**MonthlyCharges** -- The amount charged to the customer monthly

**TotalCharges** -- The total amount charged to the customer

**Churn** -- Whether the customer churned or not (Yes or No)

## Instructions

Your task is to understand the data and prepare it for model building.
Your analysis or methods should incorporate the following steps.

1.  Hypothesis formation and Data Processing - Importing the relevant libraries and modules,
    Cleaning of Data, Check data types, Encoding Data labels etc.

2.  Data Evaluation -- Perform bivariate and multivariate analysis, EDA

See attached some useful resources \[ [Exploratory Data Analysis:
Univariate, Bivariate, and Multivariate
Analysis](https://www.enjoyalgorithms.com/blog/univariate-bivariate-multivariate-analysis)
, [Univariate, Bivariate and Multivariate
Analysis](https://youtu.be/w_Tm-H-emRo) , [Exploratory Data Analysis
(EDA) Using Python](https://youtu.be/-o3AxdVcUtQ)\]

3.  Build & Select Model -- Train Model on dataset and select the best
    performing model.

4.  Evaluate your chosen Model.

5.  Model Improvement.

6.  Future Predictions.

7.  Key Insights and Conclusion.

Upon completion of your project, you are required to write a blog post
on your thought process on medium, LinkedIn, personal blog, or any other
suitable blogging site.

## Rubrics

Hypothesis & Data Processing:

-   **Excellent:** Stated hypothesis and asked relevant questions.
    Import all relevant libraries and conduct all checks
    to make the data ready for future Analysis.

-   **Good:** Stated hypothesis and implemented few steps to check
    the quality of data.

-   **Fair:** Didn't perform adequate steps in preprocessing the data and also ignored hypothesis.

**NB:** Quality checks should involve checking data types,
missing values, and dealing with class imbalance.

Data Evaluation:

-   **Excellent:** Performed more than 5 bivariate and multivariate
    analysis coupled with graphs to answer questions and hypothesis formed.

-   **Good:** Performed few bivariate and multivariate analysis coupled
    with graphs to answer some questions and hypothesis.

-   **Fair:** Performed only 1 or 2 bivariate & multivariate analysis
    but omitted key visuals like the correlation matrix.

**[NB:]{.ul}** Visuals should check collinearity, churn rate,
distributions etc.

Build and Select Model:

-   **Excellent:** Train 4 or more models and compare their combination
    of accuracy, precision, recall and F1 & F2 scores.

-   **Good:** Train less than 4 models and compare their accuracy,
    precision, recall and F1 & F2 scores.

-   **Fair:** Train only 1 model and didn't compare any accuracy,
    precision, recall and F1 & F2 scores.

Evaluate Chosen model

-   **Excellent:** Learner evaluates his/her model through k-Fold cross
    validation and explains the rationale for doing so. The results are
    further visualized on a graph.

-   **Good:** Learner only performed cross-validation with little
    explanation.

-   **Fair:** Performed only cross validation on the model without
    explaining the rationale behind.

Model Improvement

-   **Excellent:** Learner performed Hyperparameter tuning and explained
    the concept into details.

-   **Good:** Learner performed Hyperparameter tuning with little
    explanation on the concept.

-   **Fair:** Learner only performed Hyperparameter tuning.

Future Predictions

-   **Excellent:** Predicted on test sets and visualized the results via
    Confusion Matrix with detailed explanation of Confusion Matrix
    visual.

-   **Good:** Predicted on test data and only visualized on Confusion
    Matrix without any explanation of the graph.

-   **Fair:** Only predicted on test data.

Key Insights and Conclusion

-   **Excellent:** Provide a vivid conclusion on the process by
    providing 5 or more key insights from the analysis, challenges, and
    the way forward.

-   **Good:** Gave a conclusion by providing two of either key insights,
    challenges, and way forward.

-   **Fair:** Provided only key insights as conclusion.
