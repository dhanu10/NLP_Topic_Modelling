# Project Name
> NLP Topic Modelling for Bank's Customer Complaint Data, Project Group members - Dhananjay Joshi and Shajiv Kalangath



## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
This project is for data analyst working in a Bank looking into Customer Complaint database and categorizing them into high level themes.
Customer complaints from historical record vary from few charaters to few thousand charaters. These need to be appropriate pre-processed, tokenized, lemmatized.
Once standard NLP processing is done, clean output needs to be fed to TFIDF transformer. TFIDF is further modelled using NMF i.e. Non-negative matrix factorization.
NMF allows to create and distribute complaints amongst top 5 high level themes.This is unsupervised learning.
Once Complaints are distributed amongst topics, supervised learning models are built using Logistic regression, DecisionTree and RandomForrest.
Best model is evaluated based on F1 and other standard scores.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
NMF and TFIDF provide powerful methods to build high level topic modelling. You can also play with hyperparamerters like ngrams, min_df, max_df.
LogisticRegression seems to have provided better accuracy as compared to RandomForest and DecisionTree in vanila form.
Some further tuning is possible.



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Pandas Version : 1.0.5
Numpy  Version : 1.22.3
Seaborn Version : 0.10.1
Matplotlib Version : 3.2.2
Python 3
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Various ideas were picked up from searachable internet content to build the analysis in addition to lectures in upgrad.


## Contact
Created by [@dhanu10] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
