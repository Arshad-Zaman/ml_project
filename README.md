# ml_project

## How run the prebuilt classifier and missing value estimation file we used for predicting the labels:
1. You need to have Jupyter Notebooks installed to run the files. If you don't have already, install it Jupyter Notebooks by installing Anaconda from here
[Anaconda website](https://www.anaconda.com/). You would also need to have python 3 installed to use Jupyter Notebooks as it is not included.
2. To run the KNNImputer notebook, just change the `df = pd.read_csv('datasets/TrainData1.txt', na_values='1.00000000000000e+99', header=None, delim_whitespace=True)`,
line 2 to which TrainData file or TestData file you are running it on and also change the features variable on line 3 to the amount of features you have.
3. To run the 
