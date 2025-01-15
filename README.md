# Vehicle-Loan-Default-Analysis-Using-Python

# Project Description:
I undertook a comprehensive data analytics project titled "Vehicle Loan Default Analysis". This project aimed to analyze factors influencing vehicle loan defaults and develop a predictive model to assess default risks, thereby aiding financial institutions in improving their credit risk management strategies. The analysis delved into borrower demographics, financial details, and historical credit behavior to derive actionable insights for optimizing loan underwriting processes and reducing default rates.

# Objectives:
a. Analyze borrower demographics and financial profiles to identify key factors influencing vehicle loan defaults.
b. Build a logistic regression model to predict loan default probabilities.
c. Provide insights to improve loan underwriting policies and credit risk assessment.
d. Suggest strategies to optimize risk management and minimize defaults.

# Dataset Description:
The dataset consisted of 233,154 rows and 41 columns and included both numerical and categorical data. It was sourced from GitHub and contained details about:
Borrower demographics (e.g., age, employment type, location).
Loan details (e.g., disbursed amount, loan-to-value ratio).
Credit history (e.g., credit score, number of active and overdue accounts).
Identification details (e.g., Aadhar, PAN, voter ID).
The dataset offered sufficient depth for building machine learning models to predict potential loan defaulters.

# Tools and Technologies:
I utilized Python for data analysis and modeling, leveraging the following libraries and tools:
a. Pandas for data manipulation and analysis.
b. NumPy for numerical computations.
c. Matplotlib and Seaborn for data visualization.
d. SciPy for advanced statistical computations.
e. Scikit-learn for machine learning modeling, including logistic regression.
f. Jupyter Notebook via Anaconda for seamless coding, visualization, and documentation.

# Key Features of Analysis:
Data Preprocessing:
a. Identified and addressed missing values (e.g., filled 7,661 missing entries in the 'employment type' column using mode).
b. Standardized variable names for consistency.
c. Exploratory Data Analysis (EDA):
d. Analyzed the distribution of the target variable (loan default status): ~78% non-defaulters and ~22% defaulters.
e. Explored borrower demographics and employment types, revealing a higher default risk among younger and self-employed borrowers.
f. Examined the impact of credit bureau scores and historical credit behavior on default probabilities.

# Statistical Insights:
a. Identified significant correlations between overdue accounts, low credit balances, and higher default risks.
b. Highlighted the importance of longer credit histories and fewer loan inquiries in reducing default probabilities.

# Model Development:
Built a logistic regression model after encoding categorical variables and standardizing features.

# Evaluated model performance using metrics like:
Accuracy Score: 78.7%
Confusion Matrix
Classification Report (Precision, Recall, F1-score)
Addressed challenges related to class imbalance.

# Key Findings:
a. Borrowers aged 25-35 are at a higher risk of defaulting, while those over 40 show lower risk.
b. Self-employed individuals are more likely to default compared to salaried individuals.
c. Aadhar cards are the most common form of borrower identification.
d. Defaulters tend to have lower credit scores and higher delinquent account counts.
e. Primary account details significantly influence default risk, while secondary accounts show minimal impact.

Conclusion:
This project demonstrated the effective use of Python and statistical methods in analyzing vehicle loan default risks. By building a predictive logistic regression model, I have provided actionable insights to financial institutions for enhancing their credit risk management strategies. The project's findings contribute to optimizing loan approval processes and mitigating default rates, showcasing my analytical expertise and problem-solving skills in the banking domain.
