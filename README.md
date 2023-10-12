# Explainable Ponzi Schemes Detection on Ethereum

This repository stores the dataset and the source code used for the experiments presented in the paper

> Explainable Ponzi Schemes Detection on Ethereum

The repository is organized as follows:

- The directory `bytecodes` contains the bytecodes of some of the smart contracts used in our analysis. 

- The directory `dataset` contains the files to carry on the analysis. In particular, the files `dataset/dataset.csv` and `dataset/targets.csv` contain the values of features and the relative labels, respectively.

- The directory `notebook` contains the jupyter notebooks used for the paper, more precisely: 
           
    + `notebook/plot_features.ipynb` is used to generates the plots with the features distributions;
           
    + `notebook/paper_experiments.ipynb` contains the code to perform the classification experiments described in the paper, and it saves the best classifier as pickle
           
    + `notebook/best_classifier_shap_v2.ipynb` contains the code to perform the shap analysis and generate the relative figures taking in input the best classifier obtained through the previous notebook.


