# 08_Zyfra_RegressionModel

## About this Project

This project takes gold filtration data gathered by the technology and logistics company Zyfra and seeks to train a linear regression model to predict final recovery of gold. It constitutes a thorough sanitation and examination of a complex, multi-layered dataset.

The main takeaway from this project was how to approach linear regression model training when handling a very large feature set. It involves multiple extra steps of validation in the preprocessing and pretraining stages.

## Running it Yourself

The Jupyter notebook is self-contained and reflects the outputs of the code contained within. If you would like to connect to your own environment and run the notebook, or make changes on your own fork of the repo, you may do so after cloning. Make sure the environment is either based in the upper-level folder to which you clone the repo, or be sure to replace the dataset file references with a direct local reference to the /datasets/ folder on your machine. 

The project relies on scipy 1.14 and scikit-learn 1.5.1. It uses plotly 5.24.1 which requires the nbformat package to be at least 4.2.0. Check your ipykernal to make sure it is up to date. The project is stable with Python 3.11.