# D(St)reams of Anomalies

##  The real world does not slow down for bad data

1. Set up a data science project structure in a new git repository in your GitHub account
2. Download the benchmark data set from https://www.kaggle.com/boltzmannbrain/nab
3. Load the one of the data sets into panda data frames
4. Formulate ideas on how feature engineering would help the dataset to establish additional value - exploratory data analysis
5. Build one or more anomaly detection models to determine the anomalies using the other columns as features
6. Document your process and results
7. Commit your notebook, source code, visualizations and other supporting files to the git repository in GitHub

--------------------------------------------------------------------------------------------------
###### Problem:
Build Anomaly Detection Model to determine the anomalies using the other columns as features

###### Data Set Analysis
- https://www.kaggle.com/boltzmannbrain/nab#realTweets.zip
- Chosen Dataset: **Twitter_volume_AMZN.csv**
- Over 15,000 instances
- Nice Dataset with good no. of Instances and Two attributes - Timeseries and Value
- Applied Isolation Forest and One Class SVM models to determine the anomalies

###### - Relevant Notebook: **Anomaly.ipynb** under **_/notebook_**
          All the visualizations and code could be found here consolidated and documented.
          
###### - Data : **Twitter_volume_AMZN.csv** under **_/data_**
