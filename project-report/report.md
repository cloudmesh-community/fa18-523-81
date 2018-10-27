
# Analysis of Global Commodity Statistics using PySpark and Watson Analytics :hand: fa18-523-79, fa18-523-81, fa18-523-82


## Abstract

Economists, governments, trading organizations and even general public may be curious to know about the international trading patterns between different nations across the globe on various commodities. For example, one may be curious to get answers to some interesting questions like which is the largest importer of steel in the world? Which country has the highest growth in sheep production? What is America’s chocolate consumption this year? These kinds of questions can be answered by analyzing the huge volume of data that is collected from the trading transactions that happens globally between various countries. The idea is to do exploratory data analysis to find patterns and insights that may be helpful in answering such questions or raise more such new questions from observations.

## Keywords

fa18-523-79, fa18-523-81, fa18-523-82, Exploratory Data Analysis, Python, PySpark, HDFS, HBase, Watson Analytics


## Introduction

This dataset contains import and export volumes for 5,000 commodities across most of the countries on the globe over the past 30 years. Trade across the globe plays a prominent role in the economy of a nation. We are looking ahead to check for any peculiar patterns in the commodities traded by different countries in accordance with time in the past 30 years. We have imported the dataset from the UNDate site published by the United Nations Statistics Division. The dataset is a 1.2 GB sized dataset and we aim to illustrate meaningful correlations among different volumes of commodities traded by different countries in different years.

## Data 

The dataset was provided by United Nations Statistics division on the UNData website. It consists of data for over 30 years until 2016 covering all nations in the world and around 5000 plus commodities. It has over 3.5 million transactions/records with 10 columns. The total size of the dataset was 1.2 Giga bytes. The 10 variables names are: country, year, commodity code, commodity name/type, flow (import or export), trade in USD, weight in kg, quantity name, quantity and category. There are some missing values as well as outliers in the data. Hence, the data is dirty and needs good amount of cleaning and preprocessing.

## Related work 

We have found an earlier work on this dataset, that focused on specific goals about finding the trading patterns for a nation. It has taken only a sample of this dataset than whole data and was more focused on specific countries.

## Visualizations 

We will look at different kinds of visualizations like boxplots, frequency distributions, histograms, bar plots, density plots, etc. of each variable/feature depending on if it is categorical or numerical variable. 
We will also look at heat maps on correlation matrix between the variables. We may also use geographical plots to visualize the trade volume of each country on map. We shall be using python packages for visualization like Matplotlib, Seaborn, Plotly, Geographical plots majorly. We may also be using d3.js for interactive web-based visualizations.

## Technologies to be used

We will be programming in Python 3, which is an Object Oriented Programming language. It has got excellent tools and packages for Data analysis, visualization, machine learning, deep learning. We will be using Numpy, Pandas, Matplotlib, Seaborn, PySpark, SQLAlchemy etc. like packages that are required for our exploratory data analysis.

## Summary

## Future Work

Though in this project we will be focusing more on big data storage and retrieval, data preprocessing and exploratory data analysis, there is scope to do more work on this by building predictive models using various machine learning, deep learning or forecasting models, depending on the problem statement or goal we set.

## Acknowledgement

We would like to thank the United Nations Statistics Division for kindly publishing this dataset on UNData site. We would also like to thank the professor Dr. Gregor von Laszewski for his valuable inputs in helping us to choose this dataset and also for all the guidance he has provided. We would like to appreciate the effort of the associate instructors for their timely help on Piazza.
