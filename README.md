# Decision Tree Classifier

Decision tree classification and regression with scikit-learn, covering the
core workflow from training through tuning.

## Examples

| # | Task | Dataset | Notes |
| --- | --- | --- | --- |
| 1 | Classification | Iris | `DecisionTreeClassifier`, tree visualized with `plot_tree` |
| 2 | Regression | California housing | `DecisionTreeRegressor`, evaluated with MSE |
| 3 | Feature importance | Wine | Ranks features by `feature_importances_` |
| 4 | Decision boundaries | Synthetic (`make_classification`) | Visualizes how a shallow tree partitions 2D space |
| 5 | Hyperparameter tuning | Digits | `GridSearchCV` over depth, min-samples-split, min-samples-leaf |

## Running it

```bash
pip install scikit-learn matplotlib
jupyter notebook decision_tree_classifier.ipynb
```

## Requirements

- Python 3.8+
- scikit-learn, matplotlib, numpy
