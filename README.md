# Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee

## AIM:
To write a program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Read employee age, experience, salary, and churn status data.
2. Train the Decision Tree Classifier using the given employee data.
3. Read the details of the employee and predict the churn status.
4. Display whether the employee will churn or not churn.


## Program:
```
from sklearn.tree import DecisionTreeRegressor

X = [[1], [2], [3], [4], [5], [6], [7], [8]]
y = [20000, 25000, 30000, 35000, 40000, 45000, 50000, 60000]

model = DecisionTreeRegressor(random_state=42)
model.fit(X, y)

experience = float(input("Enter Years of Experience: "))

salary = model.predict([[experience]])

print("Predicted Salary:", salary[0])
```


Developed by: NAREN.V
RegisterNumber:  212225080035


## Output:
![Decision Tree Regressor Model for Predicting the Salary of the Employee](sam.png)


## Result:
Thus the program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee is written and verified using python programming.
