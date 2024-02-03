# Dissertation
Primary Dissertation Repo (February 2024)



# Structure of Repo

## Dissertation_Drafts

November. December 2023 folders - prior drafts of disseration. 
The February 2024 folder is the most current. This represented the submission of the full dissertation for supervisor review.




## Metrics Psuedocode

Text files with a the psuedocode for each of the XAI metrics built for this disseration.



## Notebooks


### XAI Notebooks 
Contains the .ipynb Python Notebooks. 

The NN model building is done in the Primary Model CC Fraud NN.ipynb file. 
  - This is the first step, and stores a model in the filestructure.
  - The credit cards fraud dataset for model building and experiments is located in this folder: CreditCard_Fraud_Dataset_25KRows_LargerSet_v1-0_July2020.csv
  - Teh file Select_CC_Fraud_Features_v1_1.csv is used in the feature selection process.

Each XAI method has a dedicated Notebook.
 - The stored model is loaded and re-verified.
 - The test data is broken into 20 equal chunks for XAI scoring. After each data blocked is scored the values are written out to a file. This file is incrementally build up over time, and the end results are averaged (externally).

The statistical analysis notebook is also stored in this folder (Friedman Test.ipynb)
 - The input of the mean metric score is also located here (XAI_StatTest2_RowLables_v1.xlsx).


### Statistical Analysis

 - Friedman Test.ipynb and XAI_StatTest2_RowLables_v1.xlsx are replicated here.
