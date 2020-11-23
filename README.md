# xray-project

## Data Retrieval
The only code you really need to generate the datasets is the ipython notebook - ideally this should be ran in a colab environment with a GPU.
There are three main data sources: two come from different github repo's and the third is pulled from Kaggle. The Kaggle dataset is particularly large so an 
AWS bucket was utilized for this project. Feel free to set up your own and run the script - the data gets migrated from S3 to the RAW_DATA folder in the main
directory. The notebook will ask you for your credentials so just remember to have those handy.

Apart from the initial S3 data setup everything in the notebook should be able to run sequentially.

## Analysis - Interpretability
Included is a briefing on the concept of Interpretability using SHAP

