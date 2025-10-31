# EEE_511-individual-two-moons
Two-moons classifier — training, decision boundary, and confusion matrix on provided test data.
# EEE 511 – Two-Half-Moons Classifier (Individual Testing)

This repo contains the code for testing the MLP classifier trained on the two-half-moons dataset.

## Files
- `two_moons_train.ipynb` – loads `2halfmoonsTrain.csv`, trains MLP, plots decision boundary and loss, and **evaluates** on `2halfmoonsTest.csv`.
- `2halfmoonsTrain.csv` – instructor-provided training set (800 samples).
- `2halfmoonsTest.csv` – instructor-provided test set (200 samples).
- (optional) `requirements.txt` – Python packages.

## How to run
1. Open the notebook in Jupyter / Colab.
2. Make sure both CSV files are in the same folder as the notebook.
3. Run all cells.  
4. The last cell will print:

- confusion matrix (counts)
- confusion matrix (normalized)
- TP, FP, FN, TN
- accuracy, precision, recall, F1
