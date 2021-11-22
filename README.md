# Final Project Big Blue Data Academy


## Author:
Spyros Travlos

## Project Title:
TCGA Clustering


## Folder Structure:

#### Data
data_retrieval: Notebook for retrieving data using xenaPython API
 \n sample_categories: Notebook for matching TCGA samples with corresponding cancer categories
#### Modelling
Clustering_tcga: Notebook with clustering on tcga samples \n
Supervised_healthy_vs_unhealthy: Notebook for classifying TCGA (cancerous) vs GTEx(healthy) samples \n
Supervised_categories: Notebook with multi-class classification of samples into cancer categories
#### Presentations
Contains presentations of the findings

#### Reports
Project Report

## Project description

In this project samples from two different studies (TCGA, GTEx) have been used. Using these data we firstly performed unsupervised learning (clustering) on cancerous samples to group samples into cancer categories. Then two classifiers have been built: The first one predicts whether a sample is a healthy or an unhealthy one and the second one predicts under which cancer category the sample falls into.
