# DU-test
This is an exercise in Machine Learning which was given by Descartes Underwriting. 
The aim was to design a code in Python.
This project is able to make a prediction on the datasets "train_auto.csv" and "test_auto.csv" of target "TARGET_FLAG". 
This project gives the value of the performance of the several algorithms tested.
This project also generates a csv file with the predictions "TARGET_FLAG.csv" associated to the most appropriate metric.

The project is based on three codes which work as:

1) A data exploration is done with the file "data-exploration.ipynb"
2) The data preparation for modelling purposes is done with the file "data-preparation.ipynb". This code generates two files with prepared datas based on "train_auto.csv" and "test_auto.csv". The two output files are named "train_data_preparation.csv" and "test_data_preparation.csv"
3) Finally, based on the files which contain prepared datas, the modelling part is done through "data-modelling.ipynb". It provides the performance of the several algorithms which were tested and a csv file with the predictions "TARGET_FLAG.csv" associated to the most appropriate algorithm.