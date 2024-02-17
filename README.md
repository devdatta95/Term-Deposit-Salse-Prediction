# Term-Deposit-Salse-Prediction-
Using the collected from existing customers, build a model that will help the marketing team identify potential customers who are relatively more likely to subscribe term deposit and thus increase their hit ratio

Try to balance the data set using Oversampling or Undersampling technique and trained the best model

input variables:
bank client data:
age (numeric)
job : type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')
marital : marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)
education (categorical: 'tertiary', 'secondary', 'unknown', 'primary')
default: has credit in default? (categorical: 'no','yes')
balance: total account balance (numeric)
housing: has housing loan? (categorical: 'no','yes')
loan: has personal loan? (categorical: 'no','yes')
related with the last contact of the current campaign:
contact: contact communication type (categorical: 'cellular','telephone','unknown')
day: last contact day of the month (numerical)
month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.
other attributes:
campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
previous: number of contacts performed before this campaign and for this client (numeric)
poutcome: outcome of the previous marketing campaign (categorical: 'failure','other','success', "unknown")
Output variable (desired target):
Target: has the client subscribed a term deposit? (binary: 'yes','no')
