# Identify-Customer-Segment
Identify Customer Segment for a Mail Order company using Kmeans Clustering analysis

## Motivation
This project aims to apply **unsupervised learning techniques** to **identify segments of the population that form the core customer base for a mail-order sales company in Germany** based on 2 dataset: the demographics subset of Germany population, and the company's customer datset. 
These segments can then be used to direct marketing campaigns towards audiences that will have the highest expected rate of returns. The data represents a real-life data science task.


## Project Files

1. Data files

The data for this project consist of 4 files:
- Udacity_AZDIAS_Subset.csv: demographics data for the general population of Germany; 891211 persons (rows) x 85 features (columns) - cannot be shared as it's private data
- Udacity_CUSTOMERS_Subset.csv: demographics data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns) - cannot be shared as it's private data
- Data Dictionary.md: all features in the data are in German, the data dictionary translated these features and their meanings to English
- AZDIAS_Feature_Summary.csv: a summary of feature attributes, including information level, data type, and codes for missing or unknown values

2. Work files

Identify_Customer_Segments.ipynb: main work file where analysis is developed, consists of 4 parts: 
- Explore data
- Features Engineering (scale continuous features and one hot encoding categorical features)
- Perform Principle component analysis (PCA)
- Perform k-means clustering 

## Installation/Requirement

The code is written in Python3. To run the Python code, you will need to install necessary packages: pandas, numpy, scikitlearn and their dependencies using `pip install` or `conda install`.  

## License
Under MIT license which means it's an open/public project, please feel free to download, make changes and give me feedback



