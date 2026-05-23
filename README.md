# Gene Expression Classification with Support Vector Machines

Prediction of leukemia subtypes from high-dimensional gene expression data using Support Vector Machine (SVM) classifiers.

The project compares predictive performance:
- using the complete set of 2000 genes,
- after variance-based filtering of the top 5% most variable genes.

---

## Methods

The analysis includes:

- exploratory data analysis,
- stratified train/test split,
- SVM classification,
- hyperparameter tuning with cross-validation,
- comparison of linear and RBF kernels,
- variance-based dimensionality reduction,
- evaluation of overfitting and generalization performance.

---

## Main Findings

Variance-based filtering is associated with:
- higher cross-validation accuracy,
- improved test accuracy,
- reduced train-test performance gap,
- more stable predictive performance across folds.

The best-performing model is an RBF SVM trained on the filtered feature space.

---

## Repository Structure

```text
data/
└── gene expression dataset

report/
├── Task_Homework03_00.ipynb
├── Task_Homework03_00.pdf
└── Quarto rendering source
```

---

## Reproducibility

Render the final PDF report with:

```bash
quarto render report/Task_Homework03_00.ipynb --to pdf
```

---

## Technologies

- Python
- pandas
- NumPy
- scikit-learn
- matplotlib
- Quarto

---

## Author

**Henri Vasserot**  
MSc in Data Science — University of Trento