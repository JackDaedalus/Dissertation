# Dissertation
Primary Dissertation Repo (February 2024)



# Structure of Repo

## Dissertation

This folder contains the submission of the full dissertation document(pdf).




## Metrics Psuedocode

Text files with a the psuedocode for each of the XAI metrics built for this disseration.



## Notebooks


### XAI Notebooks 
Contains the .ipynb Python Notebooks. 

The NN model building is done in the Primary Model Create CC Fraud NN Final.ipynb file. 
  - This is the first step, and stores a model in the filestructure.
  - The credit cards fraud dataset for model building and experiments is located in this folder: CreditCard_Fraud_Dataset_25KRows_LargerSet_v1-0_July2020.csv
  - The file Select_CC_Fraud_Features_v1_1.csv is used in the feature selection process.

Each XAI method (SHAP, LIME, ANCHOR, and DiCE) has a dedicated Notebook.
 - The stored model is loaded and re-verified.
 - The test data is broken into 20 equal chunks for XAI scoring. After each data blocked is scored the values are written out to a file. This file is incrementally built up over time, and the end results are averaged (externally).

The statistical analysis notebook is also stored in this folder (XAI Output Statistical Analysis.ipynb)
 - The input of the mean metric score is also located here (XAI_StatTest2_RowLables_v1.xlsx).
 - A secondary analysis was conducted in XAI Output Statistical Analysis Two.ipynb to verify the primary statistical review (data stored in XAI_StatTest2_RowLables_v2.xlsx).

The following notebooks were created for function operations that are shared across each of the XAI metrics experiment notebooks.
  - DS_Model_Build_Evaluation_Functions.ipynb
  - DS_Visualisation_Functions.ipynb
  - XAI_Experiment_Functions.ipynb
  - XAI_Metrics_Functions.ipynb


During runtime additional output files to verify XAI methods will be produced.

### Statistical Analysis

 - XAI Output Statistical Analysis.ipynb and XAI_StatTest2_RowLables_v1.xlsx are replicated here.


## Experiment Structure

![TUD Dissertation Figure One v1-2 260923](https://github.com/JackDaedalus/Dissertation/assets/21222832/096ea28b-7865-40b3-86e8-27a2a44d881e)
