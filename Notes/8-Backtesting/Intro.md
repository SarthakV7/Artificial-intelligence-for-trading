# Backtest Validity

![](51-55.png)
![](53-25.png)
![](54-48.png)
![](55-11.png)

# Backtest Overfitting
[This website](http://datagrid.lbl.gov/backtest/index.php) is useful for exploring backtest overfitting.

# Overtrading 

Trading in larger sizes than would be optimal. If the expected size of mis-pricing or arbitrage is 10 basis point, then no model should have been trade in such a way as to have 15 basis point of market impact. As this can not be sustainably profitable.

# Backtest Best Practices

![](02-58.png)

# Structural Changes

![](08-32.png)

# Gradient Boosting

Adaboost:

1. First weak learner minimize the number of errors:
![](12-30.png)

2. Second weak learner focus on the previously mis-classified points by punishing more on the previously mis-classified points in the cost function. 
![](14-13.png)

3. Third, forth, ... learners do the same thing.

![](15-45.png)