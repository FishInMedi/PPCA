# PPCA
Implementation of Probabilistic Principal Component Analysis
About:
Author: Andrii Hlyvko
All code is contained in the src folder. PCA.py and PPCA.py are class files of the implementations of the
two models. The file data_utils.py is a file containing unility functions.
Two test files are provided: main.py and CIFAR_test.py. The file main.py generated a random data set and tests 
PCA and PPCA on it. The CIFAR_test.py file runs PCA and PPCA on the CIFAR-10 dataset.
To run CIFAR_test.py the user
has to either place the CIFAR-10 data in the data folder or provide the 
location of the data set in the program.
The plot folder contains the plots generated by the two test files.

Usage Example:
$ python main.py
