# README

Data analysis for `cardio_ml_practice`  
Created by Daniel Raff daniel18raff@gmail.com.


Started on Jan 26th, 2018.

`data` directory: Only raw data and metadata. These files are *not* to
be modified.

`doc` directory: text documents (eg: manuscripts, documentation, record of experiments)

`src` directory: project source code


----------------------

This is a practice machine learning project, to implement feature and model selection. I've chosen a dataset from the UCI Machine Learning Repository entitled [Heart Disease Dataset](http://archive.ics.uci.edu/ml/datasets/Heart+Disease), and have used the preprocessed cleveland data (which has 14 features and 302 observations).   

This project explores feature slection methods (L1 Regularization and Recursive Feature Elimination) as well as model selection (Logistic Regression, K Nearest Neighbors, Random Forest, and Support Vector Machine) for classifying whether or not a patient has **greater than 50% coronary artery occlusion on angiography - aka are their heart arteries blocked on visualization of these arteries**.   


----------------------
How To Run:   

For simplicity the whole project is run from the [Jupyter Notebook](src/main_analysis.ipynb)  

To run, have a working version of python and the libraries `pandas`, `sklearn`, `numpy`, `seaborn`, and `matplotlib` available, then can run cell by cell.  

Alternatively, a [pdf version](doc/main_analysis.pdf) is available in the `doc` folder.  





