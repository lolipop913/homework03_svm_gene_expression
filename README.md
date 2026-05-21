# \# Gene Expression Classification with Support Vector Machines

# 

# This project investigates the prediction of leukemia subtypes from high-dimensional gene expression data using Support Vector Machine (SVM) classifiers.

# 

# The analysis compares:

# \- classification on the full set of 2000 genes,

# \- classification after variance-based filtering of the top 5% most variable genes.

# 

# The workflow includes:

# \- exploratory data analysis,

# \- stratified train/test evaluation,

# \- hyperparameter tuning with cross-validation,

# \- comparison of linear and RBF kernels,

# \- analysis of overfitting and generalization performance.

# 

# Results show that variance-based filtering improves predictive performance and reduces overfitting in this high-dimensional setting.

# 

# \## Repository structure

# 

# ```text

# data/      -> gene expression dataset

# report/    -> notebook, Quarto source, final PDF report



Main tools

Python

scikit-learn

pandas

matplotlib

Quarto

Reproducibility



Render the report with:



quarto render report/Task\_Homework03\_00.ipynb --to pdf

Author



Henri Vasserot

MSc in Data Science — University of Trento





