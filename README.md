# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>

### Step2
<br>

### Step3
<br>

### Step4
<br>

### Step5
<br>

## Program:
```
Developed by: CHANDRAPRIYADHARSHINI C
Register number: 23013526


import pandas as pd
from sklearn import linear_model

df=pd.read_csv("cars(1).csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient",regr.coef_)
print("Intercept:",regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))
```
## Output:

### Insert your output

![image](https://github.com/Bosevennila/Multivariate-Linear-Regression/assets/144870486/aaa87578-3f71-4a64-bcdb-5c4de91c477d)


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
