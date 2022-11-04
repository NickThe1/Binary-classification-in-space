# Binary-classification-in-space

### Goal is to predict class of a galaxy via dataset of 1000 observed galaxies, which are described by 13 numerical features, the class label is known for them (0 - dwarf, 1 - ordinary).

### However, the real data is a thousand times larger and confirms the theoretical distribution of ordinary and dwarf galaxies. Thus oversampling is needed.

### Applied

- Feature engineering
- Oversampling methods: ADASYN, SMOTE, BorderSMOTE, Smoothing bootstrap
- Scaling Standatd, Robust
- Machine learning algorithms
    - 2 Fully connected neural network
    - CatBoost (with feature engineering and without)
    - Logistic Regression, SVM, Gaussian naive bayes (poor performance due to nonlinearity and impossibility to create linear features)