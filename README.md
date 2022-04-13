# ml_project

## How run the prebuilt classifier and missing value estimation file we used for predicting the labels:
1. You need to have Jupyter Notebooks installed to run the files. If you don't have already, install it Jupyter Notebooks by installing Anaconda from here
[Anaconda website](https://www.anaconda.com/). You would also need to have python 3 installed to use Jupyter Notebooks as it is not included.
2. To run the KNNImputer notebook({knn_impute.ipynb}(https://github.com/Arshad-Zaman/ml_project/blob/main/knn_impute.ipynb)), just change the `df = pd.read_csv('datasets/TrainData1.txt', na_values='1.00000000000000e+99', 
3. header=None, delim_whitespace=True)`, line 2 to which TrainData file or TestData file you are running it on and also change the features variable on line 3 to the amount of features you have.
3. To run the notebook([classifier_accuracy_comparison.ipynb](https://github.com/Arshad-Zaman/ml_project/blob/main/classifier_accuracy_comparison.ipynb)) used to compare accuracies using different prebuilt methods, change:
  - the dataframes `dataset` to path where the clea


## How run the CUSTOM KNN classifier and KNN Impute value estimation scripts:
1. For the Classifier Problem. Run the first and second cell in "Custom KNNClassifier.ipynb". All the Classification text files have been hardcoded to be extracted from the "datasets" folder and then to be saved in the "custom_KNN_results" folder.
2. For the Missing Values Problem. Run the first and second cell in "Custom KNN-MissingValues.ipynb". All the missing values text files have been hardcoded to be extracted from the "datasets" folder and then to be saved in the "custom_KNN_results" folder.