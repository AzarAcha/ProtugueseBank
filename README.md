# ProtugueseBank
Helping Portuguese Bank marketing team to predict their term plan subscription

# Problem Statement
Task 1:-Prepare a complete data analysis report on the given data.

Task 2:-Create a predictive model which will help the bank marketing team to know which customer will buy the product.

Task3:-Suggestions to the Bank market team to make customers buy the product.

# Features in the Dataset

Age :- Age of Bank Customers.\
Job - What Type of job do Bank Customer.
Marital - Marital Status.
Education - Education / Highest Qualification.
Default - Customer has defaulted or not(make mistakes or not able to return loan).
housing - Customer has House loan or Not.
loan - customer has Personal Loan or Not.
Contact - Communication Type.
Month - Last Contact Month of the year.
day_of_week - last contact day of week.
Duration - last contact duration in seconds .
campaign - number of contacts performed during this campaign and for this client.
pdays - number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted).
previous - number of contacts performed before this campaign and for this client.
poutcome - outcome of the previous marketing Campaign.
emp.var.rate- employment variation rate - quarterly indicator.
cons.price.idx - consumer price index - monthly indicator.
cons.conf.idx - consumer confidence index - monthly indicator.
euribor3m - euribor 3 month rate - daily indicator .
nr.employed - number of employees - quarterly indicator.
y - the client has subscribed a term deposit or not.


# Conclusion
Best Model is Random Forest with highest
Accuracy with 95%
Best F1 Score with 95% which balances Precision adn Recall
Precision with 93% indicates low false postives
Recall with 96% indicates low false positives

Other Models
XG Boost with accuracy, f1 score, precision and recall score more than 90%
Followed by Decision Tree and Gradient Boost
KNN with 98% recall but lower precision


# Suggestion to the Bank
The Portuguese bank should use Random Forest for client targeting while tracking its effectiveness over time because it has the best accuracy and recall. The success rate of upcoming marketing initiatives can be further increased through ongoing feature optimization and model retraining. 
