# Latent Dirichlet Allocation (LDA)

Topic modeling is a method for unsupervised classification of documents, similar to clustering on numeric data, which finds some natural groups of items (topics) even when we’re not sure what we’re looking for. 

Latent Dirichlet Allocation (LDA) is one of the most popular topic modeling methods. It is a generative statistical model that explains a set of observations through unobserved groups, and each group explains why some parts of the data are similar. In other words, each document is made up of various words, and each topic also has various words belonging to it. Thus, the aim of LDA is to find topics a document belongs to, based on the words in it.

## Data Description
The data used for this analysis is a historical dataset containing 13,087 press releases from the Department of Justice's (DOJ) website https://www.justice.gov/news. The DOJ typically publishes several releases per day and this dataset spans from 2009 to July 2018. The releases contain information such as outcomes of criminal cases, notable actions taken against felons, or other updates about the current administration. This dataset only includes releases categorized as "Press release" and does not contain those which have been labeled as "Speeches". Some releases are tagged with topics or related agencies.

The dataset can be found here: https://www.kaggle.com/datasets/jbencina/department-of-justice-20092018-press-releases 

## Rendered Notebook
View the rendered notebook on [nbviewer](https://nbviewer.org/github/kvstats/latent_dirichlet_allocation/blob/main/latent_dirichlet_allocation.ipynb).
