# Implementation-of-Linear-Regression-Using-Gradient-Descent

## AIM:
To write a program to predict the profit of a city using the linear regression model with gradient descent.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Read the dataset and select the input feature (X) and target value (y).
2. Initialize the slope (m), intercept (b), learning rate, and number of iterations.
3. Repeatedly calculate predicted values, find gradients, and update (m) and (b) using gradient descent.
4. After all iterations, use the final equation to predict profit and plot the regression line.

## Program:
```
/*
Program to implement the linear regression using gradient descent.
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
data=pd.read_csv("Startup.csv")
X=data['R&D Spend'].values
y=data['Profit'].values
X=(X-X.mean())/X.std()
m=0
b=0
learning_rate=0.01
epochs=1000
n=len(X)
for i in range(epochs):
    y_pred=m*X+b
    dm=(-2/n)*np.sum(X*(y-y_pred))
    db=(-2/n)*np.sum(y-y_pred)
    m=m-learning_rate*dm
    b=b-learning_rate*db
print("Slope(m):",m)
print("Intercept(b):",b)
y_pred=m*X+b
plt.scatter(X,Y)
plt.plot(X,y_pred)
plt.xlabel("R&D Spend (Normalized)")
plt.ylabel("Profit")
plt.title("Gradient Descent on 50_Startups Dataset")
plt.show()

Developed by: R.Ashlin Sweety
RegisterNumber: 212225040031 
*/
```

## Output:
<img width="809" height="616" alt="Screenshot 2026-04-20 101619" src="https://github.com/user-attachments/assets/4d004d88-5f03-45a5-bb9c-3c8c18f9e66f" />



## Result:
Thus the program to implement the linear regression using gradient descent is written and verified using python programming.
.
.
.
.
.
.

.
.
.
.
.

.
.
.

.
.
.
.

.

.
.
.
.
.
.

.
.
.

.
.
.
.
.
.

.
.
.
.
.
.

.
.
.
.
.

.
.
.
.

.
.....................

......
.
.
.

.
.
.
