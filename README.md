# xray-project

## Project Structure
The main structure is build off the repo https://github.com/aildnont/covid-cxr. To bolster the training three different datasources were compiled and preprocessed.
The notebook includes commands to retreive and organize the data, train three different image based models, and run interepretability analysis with LIME
and SHAP. The notebook was intended to be ran in a COLAB environment with a GPU.

## Data Retrieval
There are three main data sources: two come from different github repo's and the third is pulled from Kaggle. The Kaggle dataset is particularly large so an 
AWS bucket was utilized for this project. Feel free to set up your own and run the retrieval scripts - the data gets migrated from S3 to the RAW_DATA folder in the main
directory. The notebook will ask you for your bucket credentials so just remember to have those handy.

Apart from the initial S3 data setup everything in the notebook should be able to run sequentially.

## Analysis - Interpretability
Included is a briefing on the concept of Interpretability using SHAP

