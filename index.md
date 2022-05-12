On this page, I would like to share some works made by me. You can find my resume [here](https://spb.hh.ru/resume/03d9e35dff096d7a650039ed1f4e4e39726f7a?hhtmFrom=account_login)

List of projects:

- NYSE data dashboard
- Customer Churn Prediction
- ETL pipeline
- Cohort Analysis template
- Credit Default Scoring (Hypothesis Testing)
- Credit Card Fraud Detection
- Spread Widening prediction
- SQL scripts collection
- Tableau Sample Dashboard

### NYSE data Dashboard

Within this work I've done some basic exploratory data analysis, the main purpose of it was to make me familiar with the Dash library. The dashboard itself can be found [here](https://nyse-data.herokuapp.com/) it is fully interactive, you can hover over each graph in order to see the details, you can also zoom into details (view more navigation buttons in the upper right angle)

- The next step in creating dashboards – wrap all the visuals into bootstrap components. My very first try in this field was an app where you can enter a ticker name and watch it's candlestick chart live, needless to say it looks far more pretty than the previous dashboard, you can view preliminary version [here](https://yukontaf-stock-plot.herokuapp.com/).

### Customer Churn Prediction

[Here](churnAnalysis.html) I've done some basic EDA, the main purpose is to create an efficient model to predict the churn of the client given some parameters. I've also planned to build a web app (via streamlit) to make it easy to make predictions, especially for the part of the audience that doesn't have a configured jupyter notebook at hand. Via this work, I demonstrate the ability not only to build but also a fine-tune an ML model with optuna package.

### ETL pipeline

[This](etl.html) is not full-scale work. Via this script, I would like to demonstrate the fact that I have experience working with databases, to make this work I've created a locally running database, which can be accessed remotely (when I start a ngrok tunnel on my local machine). I've also wanted to show that I'm able to load any given table into a relational database.

### Cohort Analysis

[Here](https://github.com/yukontaf/projects/blob/master/Case6.ipynb) I've attempted to calculate several metrics and make basic plots. I've also wanted to show that I'm familiar with pandas groupby method, and using it to make plots.

In [this](cohortAnalysis.html) work I've broken the dataset down into cohorts, calculated RMF metrics and then basing on their value, implemented  'hand-crafted' clustering (where affiliation to each cluster was calculated based on heuristic rule) and then compared (RMF) this way of clustering with scikit-learn algo K-means. * This can be used as template for cohort analysis for an arbitrary dataset *  

### Credit Default Scoring (Hypothesis Testing)

In [this](creditScore.html) script written in R, I've done some exploratory data analysis and tested hypotheses concerning default, i.e. how does presence in certain social category (sex, marriage, education level) impact the returning of credit, and also answered the question if the mean credit limit differs for default and non-default groups.

### Credit Card Fraud Detection

In [this](ccFraudDetection.html) script I tried to implement a well-known anomaly detection algorithm that uses inverse PCA transformation 

### Spread Widening Prediction

In the [first](orderBook.html) script, I implemented a simple animated order book (much of the code is redundant, watch the result at the end of the file, note: in order to view an animated version you will need to download and launch the source code on your local machine). In a [second](spreadWideningPred.html) – tried to build a model which would predict if the spread becomes wider or not. To do so, I needed to deal with an extremely imbalanced dataset.

### SQL scripts

Here are some SQL scripts, written by me.

- [Basic SQL](basicSQL.html)
- [Script 1](https://github.com/yukontaf/projects/blob/master/script1.sql)
- [Script 2](https://github.com/yukontaf/projects/blob/master/script2.sql)
- [Script 3](https://github.com/yukontaf/projects/blob/master/script3.sql)
- [Script 4](https://github.com/yukontaf/projects/blob/master/script4.sql)
- [Script 5](https://github.com/yukontaf/projects/blob/master/script5.sql)
- And [here](tables.html) is a notebook where you can see the tables to which these queries are made (except for the first)

### Tableau Sample Dashboard

Under developement!
