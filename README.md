# Ensemble-Method_Stacking

Implements an ensemble method: Stacking.
- Trains two primary classifiers: a neural network and a decision tree
- Utilizes the predictions from these primary classifiers as features/input for a secondary classifier, logistic regression.
- Demonstrates the effectiveness of stacking in combining the strengths of multiple classifiers to enhance predictive
performance.

trains a neural network and a decision tree first, and then uses their predictions as input to a second classifier: Logistic Regression.
Initialized a decision tree, setting maximum depth to 2 and using the default splitting criterion.


## Structures
- Ensemble-Method_Stacking




## Dependencies
`numpy` `matplotlib` `Scipy` `Scikit-learn` `TensorFlow` `Keras`
