# SVM Tutorial: Support Vector Machines

This repository contains a short tutorial and demonstration notebook for Support Vector Machines (SVM).

## Files
- `SVM_Tutorial.pdf` - Short tutorial PDF (created separately).
- `SVM_Tutorial.ipynb` - Jupyter notebook demonstrating SVM on the Iris dataset (binary classification: Setosa vs Versicolor).
- `svm_rbf_best.joblib` - Saved best RBF model (created when notebook is run).
- `scaler.joblib` - Saved scaler (created when notebook is run).

## How to run
1. Create a Python environment with the required packages:
```
pip install numpy matplotlib scikit-learn joblib
```
2. Open `SVM_Tutorial.ipynb` with Jupyter Notebook or JupyterLab and run all cells.
3. The notebook will produce decision boundary plots, perform grid search for RBF hyperparameters, and save the best model.

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.

## References
- Cortes, C. & Vapnik, V. (1995). Support-vector networks.
- scikit-learn documentation: https://scikit-learn.org
