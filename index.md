On this page, I would like to share some works made by me. You can find my resume [here (RU)](https://spb.hh.ru/resume/03d9e35dff096d7a650039ed1f4e4e39726f7a?hhtmFrom=account_login) and [here (EN)](CV.html)

List of projects:

- Airbnb Analytical Dashboard
- Video Game Sales Analysis
- Mobile Game Data Analysis
- Landing Page Design Experiment
- Online Advertising Campaign Analysis
- Customer Churn Prediction
- ETL pipeline
- Cohort Analysis template
- Credit Default Scoring (Hypothesis Testing)
- No-show Appointment Data Exploration
- Credit Card Fraud Detection
- Spread Widening prediction
- Time Series Prediction
- SQL scripts collection

### Airbnb Analytical Dashboard

[This](https://public.tableau.com/app/profile/gleb.sokolov/viz/AirbnbAnalyticalDashboard/Dashboard1?publish=yes) Tableau Public dashboard consists of: calculated renting property occupation rate; analytical chart to choose the best property by occupation rate, review score and price per night; a ranked table of top listings by calculated potential annual revenue; average price, average occupation rate and a number of unique listings KPIs; filters by neighborhood, occupation rate and a number of reviews per the last twelve month.

### Video Game Sales Analysis

Notebook can be found [here](https://drive.google.com/open?id=1IRu9RcQBzFfvXeh1HcKoBl7DFMa_yfD0&usp=drive_fs)

**Skills**: data loading, data cleaning and preprocessing, filling missing values, EDA (exploratory data analysis), analyzing region based user profiles, measuring statistical factors, hypothesis testing.

### Mobile Game Data Analysis

Notebook can be found [here](https://drive.google.com/open?id=1IJ_lHboxyVNYnC0rRtFl8yVS35K6ycqo&usp=drive_fs)

While completing this project I have been pursuing the following objectives: to find and visualize retention, to make a decision based on the A/B test data, to suggest a number of metrics to evaluate the results of the last monthly campaign.

**Skills**: data cleaning, detecting data anomalies, python coding, data visualization, descriptive statistics, dealing with outliers, A/B tests, Shapiro–Wilk test, Levene's test, data transforms, Mann–Whitney U test, proportions z-test, bootstrapping, defining metrics.

### Landing Page Design Experiment

Notebook can be found [here](https://drive.google.com/open?id=1IPPCWhqhWUO198mick07WXR-LOvsjVoB&usp=drive_fs)

**Skills:** evaluating A/B-test design, data cleaning, data anomalies detection, checking splitting system, calculating conversion rate, calculating bounce rate, log-scale transformations, Shapiro–Wilk test of distribution normality, A/B-tests (proportions z-test, Mann–Whitney rank test), plotting results, making conclusion and giving recommendations for follow-up actions.

### Online Advertising Campaign Analysis

Notebook can be found [here](https://drive.google.com/open?id=1IJ-mXd1cyl2QQOMqbimY02ccbiFikIWe&usp=drive_fs)

**Skills:** data cleaning, CTR, CPC, CPA and CR calculation, comparing metrics with competitors, visualizing results, drawing conclusions.

### Customer Churn Prediction

[Here](churnAnalysis.html) I've done some basic EDA, the main purpose is to create an efficient model to predict the churn of the client given some parameters. I've also planned to build a web app (via streamlit) to make it easy to make predictions, especially for the part of the audience that doesn't have a configured jupyter notebook at hand. Via this work, I demonstrate the ability not only to build but also a fine-tune an ML model with optuna package.

### ETL pipeline

[This](etl.html) is not full-scale work. Via this script, I would like to demonstrate the fact that I have experience working with databases, to make this work I've created a locally running database, which can be accessed remotely (when I start a ngrok tunnel on my local machine). I've also wanted to show that I'm able to load any given table into a relational database.

### Cohort Analysis

[Here](Case6.html) I've attempted to calculate several metrics and make basic plots. I've also wanted to show that I'm familiar with pandas groupby method, and using it to make plots.

In [this](cohortAnalysis.html) work I've broken the dataset down into cohorts, calculated RMF metrics and then basing on their value, implemented  'hand-crafted' clustering (where affiliation to each cluster was calculated based on heuristic rule) and then compared (RMF) this way of clustering with scikit-learn algo K-means. *This can be used as template for cohort analysis for an arbitrary dataset*  

### Credit Default Scoring (Hypothesis Testing)

In [this](creditScore.html) script written in R, I've done some exploratory data analysis and tested hypotheses concerning default, i.e. how does presence in certain social category (sex, marriage, education level) impact the returning of credit, and also answered the question if the mean credit limit differs for default and non-default groups.

### No-show Appointment Data Exploration

[Here](noShowAppointment.html) I've made a visualization for every feature that can presumably impact the target variable (show or no-show on the given day), next, I've calculated confidence intervals for difference in show/no-show ratios in order to numerically show which features have impact on target. Then, I've build and compaired a pair of classifiers (Bernoulli and MultinomialNB), the first one showed better results with ***accuracy of 80%*** on the test sample

### Credit Card Fraud Detection

In [this](ccFraudDetection.html) script I tried to implement a well-known anomaly detection algorithm that uses inverse PCA transformation 

### Spread Widening Prediction

In the [first](orderBook.html) script, I implemented a simple animated order book (much of the code is redundant, watch the result at the end of the file, note: in order to view an animated version you will need to download and launch the source code on your local machine). In a [second](spreadWideningPred.html) – tried to build a model which would predict if the spread becomes wider or not. To do so, I needed to deal with an extremely imbalanced dataset.

### Time Series Prediction

In [this]([Google Colab](https://colab.research.google.com/drive/1WrEgv0BM4qvAEHW4d3X_41Hy2FvQshC3#scrollTo=sCRtsvD3y2jH)) notebook I implemented two fundamentally different algorithms for forecasting: the fist was simple moving average, which, in my opinion, performs poorly, and the second was deep neural network. As we can see there, DNN can gives us pretty accurate (compared with moving average) results even if our dataset is relatively small (in my case it were only 4923 points there). This work clearly demonstrates that I'm capable of performing intricate procedures for preparing dataset for forecasting with neural network and obtain reasonable results.

### SQL scripts

Here are some SQL scripts, written by me.

- [Basic SQL](basicSQL.html)
- [Script 1](https://github.com/yukontaf/projects/blob/master/script1.sql)
- [Script 2](https://github.com/yukontaf/projects/blob/master/script2.sql)
- [Script 3](https://github.com/yukontaf/projects/blob/master/script3.sql)
- [Script 4](https://github.com/yukontaf/projects/blob/master/script4.sql)
- [Script 5](https://github.com/yukontaf/projects/blob/master/script5.sql)
- And [here](tables.html) is a notebook where you can see the tables to which these queries are made (except for the first)
