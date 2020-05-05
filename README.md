# Analysis of Yelp Reviews
### Data Source

Three datasets (user, review, and business) were used for this analysis. 
All datasets are can be found on [Kaggle](https://www.kaggle.com/yelp-dataset/yelp-dataset). 
The datasets were uploaded to AWS S3 bucket s3://yelpdata-ak/yelp/yelp_academic_dataset_business.json

### Objectives

The objective is to use Apache Spark on AWS EMR while accessing data sets from AWS S3 
to analyze a few million data points.

(1) Business dataset is used to find the most abundant business types (categories).

(2) Review and Business datasets are both used to see if reviews, who leave textual 
reviews, rate businesses more or less highly as compared to the overall business rating.

(3) User and Business datasets are used to see if elite reviewers rate businesses any 
differently than regular reviewers.




### EMR Cluster and Notebook Configurations

<img src="/assets/emr_configs.png" width="400">

<img src="/assets/notebook_configs.png" width="400">

### Yelp datasets on AWS S3

<img src="/assets/AWS_S3_Yelpdatasets.png" width="400">