# Nonlinear_Productivity_Response_Model



### Model Structure: non-linear additive model
              Team Contribution = f(employee_1) + f(employee_2) + ... + f(employee_n)
where each person's contribution follows a logistic-like tranformation:
              f(x) = alpha * (beta * x) /(1 + beta * x)
where:
x: hours worked
alpha: elasticity coefficient (controls the height of the curve)
beta: curve coefficient (controls the shape of the curve)

### Estimation Method: non-linear least suqares

### Assumptions of this model:
1. Contributions follow a saturation curve
2. No sysnergy (contributions are independent and additive)
3. Other contribution = 0 (other factors)
4. No time dependence in inputs (no time series)

