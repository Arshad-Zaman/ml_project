# ml_project

## How to run MAIN MODELS THAT WILL BE USED FOR GRADING. The prebuilt classifier and missing value estimation files we used for predicting the labels:
<<<<<<< HEAD
1. You need to have Jupyter Notebooks installed to run the files. You also need to make sure that Pandas is at version 1.3.5 If you don't have already, install it Jupyter Notebooks by installing Anaconda from here
[Anaconda website](https://www.anaconda.com/). You would also need to have python 3 installed to use Jupyter Notebooks as it is not included.
=======
1. You need to have Jupyter Notebooks installed to run the files. If you don't have already, install it Jupyter Notebooks by installing Anaconda from here
[Anaconda website](https://www.anaconda.com/). You would also need to have python 3, pandas, numpy and scikit-learn installed to use Jupyter Notebooks as it is not included.
>>>>>>> 0a9cd5a1a305fdd5952b18c487988653273f9fb3
2. For Missing Values 1,2,3 and preprocessing for the classification data we run KNNImpute [notebook](https://github.com/Arshad-Zaman/ml_project/blob/main/knn_impute.ipynb), open the notebook {knn_impute.ipynb} and hit restart and run all and you will all the files that need to be cleaned on the [cleaned_datasets](https://github.com/Arshad-Zaman/ml_project/tree/main/clean_datasets) folder. It will also impute the missing values for part 2 and save them into the [results](https://github.com/Arshad-Zaman/ml_project/tree/main/results) folder.
3. For Classification1, hit restart and run all on [knn_classifier.ipynb](https://github.com/Arshad-Zaman/ml_project/blob/main/knn_classifier.ipynb) and you will have the predicted labels in the [results](https://github.com/Arshad-Zaman/ml_project/tree/main/results) folder.
4. For Classification2, Classification4, and Classification5 hit restart and run all on [random_forest_classifier.ipynb](https://github.com/Arshad-Zaman/ml_project/blob/main/random_forest_classifier.ipynb) and you will have the predicted labels in the [results](https://github.com/Arshad-Zaman/ml_project/tree/main/results) folder.
5. For Classification3 hit restart and run all on [svm_classifier.ipynb](https://github.com/Arshad-Zaman/ml_project/blob/main/svm_classifier.ipynb) and you will have the predicted labels on the [results](https://github.com/Arshad-Zaman/ml_project/tree/main/results) folder.

## How run the CUSTOM KNN classifier and KNN Impute value estimation scripts(WARNING THIS MIGHT TAKE 20 MINUTES TO RUN):
1. For the Classifier Problem. Run the first and second cell in "Custom KNNClassifier.ipynb". All the Classification text files have been hardcoded to be extracted from the "datasets" folder and then to be saved in the "custom_KNN_results" folder.
2. For the Missing Values Problem. Run the first and second cell in "Custom KNN-MissingValues.ipynb". All the missing values text files have been hardcoded to be extracted from the "datasets" folder and then to be saved in the "custom_KNN_results" folder.
