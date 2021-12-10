## Term Deposit Subscription: A Machine Learning Approach

This paper uses machine learning algorithms to predict client term deposit subscription decision in a Portuguese bank.

Link of the dataset: https://archive.ics.uci.edu/ml/datasets/Bank+Marketing

## File structure

The "script" folder contains the R code to import data, perform analysis, etc.

In "inputs", the "data" folder contains the raw data used in the analysis and the "rds_store" folder contains Cross Validation result of several algorithms to enhance analysis reproducibility.

In "outputs", the "paper" folder contains PDF version of the paper knitted from "paper.Rmd"

## How to reproduce the paper

1. Download the entire GitHub repo 

2. Extract the folder and open "bank_marketing.Rproj" in RStudio

3. Download all required R packages

3. Open "paper.Rmd" and knit it using "Knit to pdf_document2" option
