# Mortgage Modeling
This Python notebook looks at publicly available data from the CFPB pursuant to the Home Mortgage Disclosure Act of 1975. The dataset contains fields such as race, gender, income, and requested loan amount for many applicants. Based on this information, I attempt to make a machine learning model to accurately classify whether or not a particular loan would be approved. 

The dataset in total contains over 30M records and is over 12GB in size. Because of this and due to insufficient RAM on my machine, this analysis had to be conducted using Apache Spark (PySpark) instead of a friendlier framework like Pandas.

**Raw Data:** https://ffiec.cfpb.gov/data-publication/dynamic-national-loan-level-dataset
**Data Dictionary & Definitions:** https://ffiec.cfpb.gov/documentation/2019/lar-data-fields/

*Note:* Both the 2018 and 2019 records are used here. All fields & value types are identical in each year.

