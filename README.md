# ML_notebooks
A collection of ML work I've done:

smiles.ipynb: the most lengthy work as of 8 Sep 2022; generated data using RDKit, then built XGBoost/sci-kit models

rna-seq/her2-model: using rna-seq and clinical data to predict cancer status; simple logistic regression model reproduces results in literature, for her2 gene at least. Other gene correlations not reproduced in this work, may be due to processing steps with edgeR. Much of the work is not invisible in the .html and .ipnyb; see: https://github.com/patimus-prime/rnaseq_her2

MNIST_gpu: some initial work with pytorch lightning, developing a robust framework for future work; lightning reduces the chaotic-ness of approaches but still some confusing calls that have implicit methods.
