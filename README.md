# Dissertation
Primary Dissertation Repo (post October)



# Structure of Repo

## Dissertation_Drafts

November and December 2023 folders - drafts of disseration. The December 2023 folder is the most current.




## Metrics Psuedocode

Text files with a the psuedocode for each of the XAI metrics built for this disseration.




## Notebooks

### November 2023 Back Up




### XAI Notebooks 
Contains the .ipynb Python Notebooks. At the moment each notebook creates a new model each time, then generate the XAI values on a small subset of the test data, before generating the metric scores.

These notebooks will be updated in early 2024 so that;
 
 - The NN model building is done only once and stored as an input to the XAI metrics notebooks.
 - The test data is broken into 20 equal chunks for XAI scoring. After each data blocked is scored the values are written out to a file. 
This file is incrementally build up over time, and the end results are averaged. A 'mock-up' notebook of how this experiment processing will take place is included.




### Statistical Analysis
A credit default dataset was used for the initial build of the experiments notebooks. This was done for simplicity as this dataset is relatively small but has a '0' and '1' label,
in common with the primary credti card fraud dataset to be analysed in this disseration. A Python notebook carries out the Friedman and Wilcoxon-signed pairwise tests and produces the outputs.

The XL file is a mock up of the final mean XAI metrics scores.
