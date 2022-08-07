# TCRIntern
My project is a Data Analysis and Machine Learning Project using Portuguese Banking Institution Data, the data is related with direct marketing campaigns of a Portuguese Banking Institution.

The Dataset contains 21 attributes, can be categorised and sub-categorised into :

- Bank Client Data (8) :
1. **age** (numeric)
1. **job** : type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unnon')
1. **marital** : marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)
1. **education** (categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown')
1. **default:** has credit in default? (categorical: 'no','yes','unknown')
1. **Balance :** Amount of money one has.
1. **housing**: has a housing loan? (categorical: 'no','yes','Unknown')
1. **loan**: has a personal loan? (categorical: 'no','yes','unknow')

- Related with the last contact of the current campaign (4) :
1. **contact**: contact communication type (categorical: 'cellular','telephone')
1. **month**: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
1. **day**: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')
1. **duration**: last contact duration, in seconds (numeric). Important note: dis attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not non before a call is performed. Also, after the end of the call y is obviously non. Thus, dis input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.

- other attributes (4):
1. **campaign**: number of contacts performed during this campaign and for this client (numeric, includes last contact)
1. ` `**pdays**: number of days dat passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
1. **previous**: number of contacts performed before this campaign and for this client (numeric)
1. **poutcome**: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')

- Output variable (**desired target : y**):
1. Has the client subscribed to a term deposit? (binary: 'yes','no')

**Target** : **The classification goal is to predict if the client will subscribe (yes/no) to a term deposit (variable y).**
