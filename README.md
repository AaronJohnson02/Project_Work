# Project_Work

The repository is used for our work, do add a description to any changes to the programs so we can keep track of what's happening and make a list after 
this with hyperlinks to each module for easier navigation. Good luck.

I have updated the repositories with the feature extracted csv files under feature_extracted_data. The csv file of importance is the train.csv file which will be used to train our models. You may ignore the other csv files under this folder as they are intermediates and have been included to show how I modularised the collection process. The data sets from which urls are collected are listed under the data directory. All ipynb files included show the programs used to perform said feature extraction.

You may begin training your models on the train.csv. Label 0 indicates a legitimate url and 1 indicates a phishing url. Happy training!

You may use the test.csv file under the feature_extracted_directory to test the accuracy of your trained models.

All model ipynb files have been updated with precision, recall, accuaracy, training time and testing time as well as a confusion matrix. The model_comparison.csv file compares these metrics for all models. XGBoost seems to be the best in terms of accuracy as well as prediction time which are key factors for picking the optimal model.
