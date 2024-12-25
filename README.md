# CSCI303: Data Science - Support Vector Machine (SVM)

#### *Melody Goldanloo*

## Overview
This project applies Support Vector Machines (SVM) to classify Parkinson’s Disease using biomedical voice data. It evaluates multiple kernels (linear, polynomial, and RBF) and compares their performance based on key metrics like accuracy, precision, recall, and F1 score.

## Key Features
- ### Data Preprocessing:
    - Handled missing values and standardized features.
    - Visualized feature distributions and relationships.
- ### Model Development:
    - Trained SVM classifiers with linear, polynomial, and RBF kernels.
    - Tuned hyperparameters like `C` and `gamma` for optimization.
- ### Evaluation Metrics:
    - Assessed model performance with accuracy, precision, recall, F1 score, and confusion matrices.

## Technologies Used
### Libraries
- `pandas` - Data manipulation and preprocessing.
- `numpy` - Mathematical operations and handling arrays.
- `scikit-learn` - Model building and evaluation.
- `matplotlib` and `seaborn` - Data visualization.

## Dataset
- **Name:** Parkinson's Disease Dataset
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/machine-learning-databases/parkinsons/parkinsons.data)
- **Description:**
    - 195 samples with 23 features each.
    - Includes voice measurements used to distinguish between healthy individuals and those with Parkinson's Disease.
    - Target variable: status (1 = Parkinson's, 0 = Healthy).
 
## Installatation and Usage
1. Clone this repository:
  ```
  git clone https://github.com/username/csci303_svm.git
  cd csci303_svm
  ```
2. Open the `Project - SVM.ipynb` file.
3. Follow the steps outlined and run the corresponding scripts to build the model.
4. Outputs: Model accuracy, precision, recall, F1 score, and confusion matrix.

## Acknowledgements
This project was developed as part of CSCI303 - Data Science at the Colorado School of Mines. Special thanks to Professor Morgan Cox and Dr. Wendy Fisher for guidance and course resources and materials.
