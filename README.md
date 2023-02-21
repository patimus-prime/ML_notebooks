# ML_notebooks
A collection of statistical analysis and ML work I've done:

SMILES_2_0: predict target protein class of small molecules; generated data using RDKit and Mordred, then built XGBoost/sci-kit models; tentatively trying out PyTorch DL models

high_throughput_analysis: Identifying approx. 100 great candidates from 100,000 strains; problems introduced by multiple instruments and time-series effect

rna-seq/her2-model: using rna-seq and clinical data to predict cancer status; simple logistic regression model reproduces results in literature, for her2 gene at least. Other gene correlations not reproduced in this work, may be due to processing steps with edgeR. Much of the work is not invisible in the .html and .ipnyb; see: https://github.com/patimus-prime/rnaseq_her2

MNIST_gpu: some initial work with pytorch lightning, developing a robust framework for future work; lightning reduces the chaotic-ness of approaches but still some confusing calls that have implicit methods.
