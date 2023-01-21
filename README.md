# How to do EDA Exploratory Data Analysis using Colab Jupyter Notebook and Github
The main purpose is to show how to use Github as a data repository that you can access directly from other applications. In this case, I use Google Colab to ingest the raw data using !wget in the notebook. You could also do the same thing from a Docker container, AWS Lambda function, or a regular website on shared hosting, etc. The point is to have that option, and to be able to use it if it makes sense for your application. You could even use Github Actions with crontab to schedule regular downloads to refresh the data files. Just be mindful of the file size limit and run time quotas on Github.

# colab_eda_test
Sample data files for use with Colab notebook:

- [2015 Street Tree Census - Tree Data](https://data.cityofnewyork.us/Environment/2015-Street-Tree-Census-Tree-Data/uvpi-gqnh/data)
- [Healthcare dataset](https://www.kaggle.com/datasets/kanikakhera/healthcare-dataset)
- [Patient survival prediction dataset](https://www.kaggle.com/datasets/sadiaanzum/patient-survival-prediction-dataset?select=Dataset.csv)
- [LA County restaurant inspections and violations dataset](https://www.kaggle.com/datasets/meganrisdal/la-county-restaurant-inspections-and-violations?select=inspections.csv)

## How to use:
1) Open the Jupyter Notebook: colab_explore_data_trees.ipynb
2) Save the notebook in your account
3) Explore any of the datasets using pandas. Try some visualizations with matplotlib... 

The Tree Census data comes from NYC Open Data: 
https://data.cityofnewyork.us/Environment/2015-Street-Tree-Census-Tree-Data/uvpi-gqnh/data
The data file was truncated due to the upload file size limit on Github (25 MB max).

The other data sets are there for you to practice further.

Have fun!
