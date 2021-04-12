# AI for Trading

This repo contains my work to Udacity nanodegree [AI for Trading](https://www.udacity.com/course/ai-for-trading--nd880).

## Table of Contents

### 1. Trading with Momentum. [Project](1-Trading with momentum/project_1_starter.ipynb)

* Learn basics of [stock markets](Notes/1-Trading-with-momentum/stock-market-data.md). Learn how to calculate [stock returns and design momentum trading strategy](Notes/1-Trading-with-momentum/returns-momentum.md).

### 2. Breakout Strategy. [Project](2-Breakout strategy/project_2_starter.ipynb)

* Learn about the overall [quant workflow](Notes/2-Breakout-strategy/quant-workflow.md), including alpha signal generation, alpha combination, portfolio optimization, and trading.

* Learn the [importance of outliers](Notes/2-Breakout-strategy/outliers.md) and how to detect them. Learn about methods designed to handle outliers.

* Learn about [regression](Notes/2-Breakout-strategy/regression.md), and related statistical tools that pre-process data before regression analysis. Learn commonly-used [time series](Notes/2-Breakout-strategy/time_series.md) models.

* Learn about stock [volatility](Notes/2-Breakout-strategy/volatility.md), and how the GARCH model analysis volatility. See how volatility is used in equity trading.

* Learn about [pair trading](Notes/2-Breakout-strategy/pair.md), and study the tools used in identifying stock pairs and making trading decision.

### 3. Smart beta and portfolio optimization. [Project](3-Smart beta and portfolio optimization/project_3_starter.ipynb)

* [Overview of stocks, indices, and funds](Notes/3-Porfolio-optimization/Fund.md). Learn about [ETFs](Notes/3-Porfolio-optimization/ETFs.md).
* Learn fundamentals of [portfolio risk and return](Notes/3-Porfolio-optimization/Portfolio.md).
* Learn how to [optimize portfolios](Notes/3-Porfolio-optimization/Optimization.md) to meet certain criteria and constraints. 

### 4. Alpha Research and Factor Modeling. [Project](4-Alpha research and factor modeling/project_4_starter.ipynb)

* Learn [factors](Notes/4-Alpha-Research-and-Factor-Modeling/Factors.md) and how to convert factor values into portfolio weights in a dollar neutral portfolio with leverage ratio equals to 1 (i.e., standardize factor values).
* Learn [fundamentals of factor models and type of factors](Notes/4-Alpha-Research-and-Factor-Modeling/Factor-Model.md). Learn how to compute [portfolio variance using risk factor models](Notes/4-Alpha-Research-and-Factor-Modeling/Risk-Factor-Model.md). Learn [time series and cross-sectional risk models](Notes/4-Alpha-Research-and-Factor-Modeling/Cross-Sectional.md).
* Learn how to use [PCA](Notes/4-Alpha-Research-and-Factor-Modeling/PCA.md) to build risk factor models. 

### 5. Intro to NLP. [Project](5-NLP on financial statement/project_5_starter.ipynb)
NLP pipeline consists of text processing, feature extraction, and modeling.

* Basic NLP Analysis: Learn quantitatively measure readability of documents using readability indices, how to convert document into vectors using bag of word and TF-IDF weighting, and metrics to compare similarities between documents.

### 6. Sentiment Analysis with Neural Networks. [Project](6-Sentiment analysis with neural networks/project_6_starter.ipynb)

* [Neural Network Basics](Notes/6-Sentiment-analysis-with-neutral-networks/README.md): Learn maximum likelihood, cross entropy, logistic regression, gradient decent, regularization, and practical heuristics for training neural networks.


### 7. Combining Signals for Enhanced Alpha. [Project](7-Combining signals for enhanced alpha/project_7_starter.ipynb)

* [Decision Tree](Notes/7-Combining-signals-for-enhanced-alpha/README.md): Learn how to branching decision tree using entropy and information gain.

* [Model Testing and Evaluation](Notes/7-Combining-signals-for-enhanced-alpha/Evaluation.md): Learn Type 1 and Type 2 errors, Precision vs. Recall, Cross validation for time series, and using learning curve to determine underfitting and overfitting.

* [Random Forest](Notes/7-Combining-signals-for-enhanced-alpha/Random_forest.md): Learn the ensemble random forest method.

* Feature Engineering: Certain alphas perform better or worse depending on market conditions. Feature engineering creates additional inputs to give models more contexts about the current market condition so that the model can adjust its prediction accordingly.

* Overlapping Labels: Mitigate the problem when features are dependent on each other (non-IID).

* Feature Importance: Company would prefer simple interpretable models to black-box complex models. interpretability opens the door for complex models to be readily acceptable. One way to interpret a model is to measure how much each feature contributed to the model prediction called feature importance.

### 8. Backtesting. [Project](8-Backtesting/project_8_starter.ipynb)

* Basics: [Learn best practices of backtesting](Notes/8-Backtesting/Intro.md) and see what overfitting can "look like" in practice.

* Learn how to optimization a portfolio with transaction cost. Learn some additional ways to design your optimization with efficiency in mind. This is really helpful when backtesting, because having reasonably shorter runtimes allows you to test and iterate on your alphas more quickly.
