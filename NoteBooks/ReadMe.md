# Twitter Sentiment Analysis (PySpark)
## About
This repo contains all the notebooks used for sentimental analysis on the [Sentiment140](http://help.sentiment140.com/for-students) dataset with PySpark.
This is an Collabrative Project.


## Models used
We worked with the following models :
- Logistic Regression
- Support Vector Machines (Linear Kernel)
- Naive Bayes
 
## Features tested
- Hashing TF-IDF
- Count Vectorizer TF-IDF
- ChisQSelector
- 1-Gram, 2-Gram, 3-Gram

## Results

<img
     src="https://github.com/Devazc/twitter-sentiment-analysis/blob/main/images/features.png"
     />

<img
     src="https://github.com/Devazc/twitter-sentiment-analysis/blob/main/images/summary.png"
     />
    
## ETL Pipeline & Live Sentiment Analysis (In Progress)
Another part of this project was to implement an ETL Pipeline with Live Sentiment Analysis using our pre-trained model, Spark Streaming, Apache Kafka and Docker.
