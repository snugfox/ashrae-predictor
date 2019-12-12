# Building Energy usage predictor

Below is the list of dependancies for both the jupyter notebooks. One contains Exploratory Data Analysis named as `EDA.ipynb` and the second contains code for the model named `Model.ipynb`. Install the following dependancies through `pip` or Anaconda's `conda` package manager:
1. python 3
2. numpy
3. matplotlib
4. pandas
5. seaborn
6. scikit-learn
7. hyperopt
8. lightgbm
9. pandas_profiling
10. plotly

For the neural network, in addition to the above listed dependencies, you will need to have PyTorch (torch) installed. The Jupyter notebook `ASHRAE-NN.ipynb` contains all the code related to generating a neural network model. It includes functions that load weather, building metadata, and training/testing sets from CSV files.

## Data
Download the data from the following link `https://www.kaggle.com/c/ashrae-energy-prediction/data`. Click on the download all tab. Extract the .csv files in the same path as the .ipynb notebooks.

## Running the notebooks
The code is in a Jupyter notebook which has a .ipynb format. To run the jupyter notebook click on the "Kernal" tab. From the dropdown menu click on "Restart and run all".
