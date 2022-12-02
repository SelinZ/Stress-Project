# THESIS

BASELINE PREPROCESSING.ipynb, FITBIT PREPROCESSING.ipynb, OMSIGNAL PREPROCESSING.ipynb, STRESSD PREPROCESSING.ipynb notebooks show the 
data exploration, missing data and outlier analysis, pre-processing processes for the different data streams individually.

MERGED.ipynb notebook is where the cleaned data streams were merged based on participant_id and the Timestamp variables.

AFTER MERGE- ALL.ipynb, AFTER MERGE-BASELINE.ipynb, AFTER MERGE-FITOM.ipynb notebooks show the feature selection processes using BorutaShap
separately for three different feature sets, namely all (combined), baseline survey, and fitom (wearable sensor) feature sets.

RANDOM FOREST & BASELINE.ipynb and SVM.ipynb notebooks show the implementation of the RF and SVR (support vector regressor) machine
learning algorithms, including grid search to find the best hyperparamaters, cross-validation, and evaluating the significance of the
results achieved using Wiscoxon test. 
