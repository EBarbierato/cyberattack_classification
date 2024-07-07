# Balancing the Scale: Data Augmentation Techniques for Improved Supervised Learning in Cyberattack Detection
# Dataset Simulation and Machine Learning Pipeline

This repository outlines the steps to prepare, augment, and analyze a dataset using various machine learning models.

## Step 1: Prepare the original dataset

1. Extract the folder `Dataset_simulazione`.
2. Expand the file `D1_encoded_categorical.rar` into `D1_encoded_categorical.csv`.

## Step 2: Generate augmented datasets

1. Execute the `data_augmentation_techniques.ipynb` notebook.
2. Once the notebook has terminated, verify that the `Dataset_simulazione` folder contains the new augmented datasets:
   - `smote.csv`
   - `adasyn.csv`
   - `borderline_smote.csv`
   - `tomek_links.csv`
   - `smoteenn.csv`
   - `smotetomek.csv`

## Step 3: Execute the ML models

Execute the following notebooks:

- `RandomForestClassifier.ipynb`
- `gbm.ipynb`
- `knn.ipynb`
- `logistic_regressor.ipynb`
- `lstm.ipynb`
- `naivebayes.ipynb`
- `rnn.ipynb`
- `xgb.ipynb`

## Step 4: Feature importance

1. Execute the notebook `feature_importance.ipynb`.
2. Check that the `catboost.pdf` has been generated.

---

Enrico Barbierato (enrico.barbierato[at]unicatt.it)

