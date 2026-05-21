````markdown

\# Gene Expression Classification with SVM



Prediction of leukemia subtypes from high-dimensional gene expression data using Support Vector Machine (SVM) classifiers.



The project compares:

\- classification using all 2000 genes,

\- classification after variance-based filtering of the top 5% most variable genes.



\## Methods



\- exploratory data analysis

\- stratified train/test split

\- SVM classification

\- hyperparameter tuning with cross-validation

\- linear vs RBF kernel comparison

\- variance-based dimensionality reduction

\- overfitting and generalization analysis



\## Main result



Variance-based filtering improves predictive performance and reduces overfitting in this high-dimensional setting.



\## Repository structure



```text

data/    gene expression dataset

report/  notebook, Quarto source, final PDF report

````



\## Reproducibility



```bash

quarto render report/Task\_Homework03\_00.ipynb --to pdf

```



\## Author



Henri Vasserot

MSc in Data Science — University of Trento



```

```



