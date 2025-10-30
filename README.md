# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1<br>Import Pandas library.
### Step2<br>Import Linear_model from sklearn.
### Step3<br>Read the csv file using pandas library.
### Step4<br>Enter the parameters of the linear function.
### Step5<br>Print the parameters of the linear function.


## Program:
```
Name:Janani Gowrisankar
Register No:212224100022
```
```
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("car (1).csv")
x=df[['Weight','Volume']]
y=df['CO2']
regr=linear_model.LinearRegression()
regr.fit(x,y)
print('Coefficients:',regr.coef_)
print('Intercept:',regr.intercept_)
predictedCO2=regr.predict([[3300,1300]])
print(predictedCO2)

```
## Output:

### Insert your output

<img width="1226" height="594" alt="image" src="https://github.com/user-attachments/assets/9cfd1e09-b183-4a97-bcfa-6fa817317bf8" />


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
