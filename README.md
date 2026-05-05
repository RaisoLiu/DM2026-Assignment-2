# NYCU Data Mining (Spring 2026) Assignment 2

## Requirements

- Python 3.9+
- NumPy
- Pandas
- Matplotlib
- scikit-learn
- mlxtend
- scipy

Install dependencies:
```bash
pip install -r requirements.txt
```

## How to Run

Run the notebooks in the following order:

1. `Q1_KFold_CV.ipynb` -- Q1: K-fold Cross-Validation on NYCU_Iris dataset
2. `Q2_SVM.ipynb` -- Q2: SVM classification with hyperparameter tuning
3. `Q3_Association_Rules.ipynb` -- Q3: FP-Growth association rule mining
4. `Q4_PCA_KMeans.ipynb` -- Q4: PCA dimensionality reduction and K-Means clustering
5. `Q5_Enhanced_KMeans.ipynb` -- Q5: Enhancing K-Means with association rule mining

Each notebook can be executed via Jupyter or from the command line:
```bash
jupyter nbconvert --to notebook --execute <notebook_name>.ipynb --output <notebook_name>.ipynb
```

Report figures are saved automatically to `report/figures/`.

To compile the LaTeX report:
```bash
cd report && pdflatex report.tex && pdflatex report.tex
```

## File Structure

```text
.
├── Q1_KFold_CV.ipynb                       # Q1: K-fold Cross-Validation
├── Q2_SVM.ipynb                            # Q2: SVM Classification
├── Q3_Association_Rules.ipynb              # Q3: Association Rule Mining
├── Q4_PCA_KMeans.ipynb                     # Q4: PCA + K-Means
├── Q5_Enhanced_KMeans.ipynb                # Q5: Enhanced K-Means
├── README.md
├── requirements.txt
├── data/
│   ├── mobile_price.csv
│   └── NYCU_Iris.csv
├── model/                                  # Custom model from Assignment 1
│   ├── activations.py
│   ├── gradients.py
│   ├── linear_model.py
│   ├── metrics.py
│   └── utils.py
├── figures/
├── results/
└── report/
    ├── report.tex
    ├── figures/
    └── DM_asg2_413551030.pdf
```
