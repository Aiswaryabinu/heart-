This repository contains code and resources for your AI & ML internship project, focusing on Decision Tree and Random Forest classifiers.

## Mini Guide

Follow these steps to complete your project:

### 1. Train a Decision Tree Classifier and Visualize the Tree
- Use a suitable dataset (e.g., Iris, Titanic, or any classification dataset).
- Train a `DecisionTreeClassifier` from scikit-learn.
- Visualize the decision tree using `plot_tree` or `export_graphviz`.

### 2. Analyze Overfitting and Control Tree Depth
- Observe performance on train vs. test data.
- Experiment with `max_depth`, `min_samples_split`, etc., to control complexity and reduce overfitting.
- Plot accuracy or loss curves as a function of tree depth.

### 3. Train a Random Forest and Compare Accuracy
- Train a `RandomForestClassifier` on the same dataset.
- Compare the accuracy and interpretability of the random forest vs. the single decision tree.

### 4. Interpret Feature Importances
- Extract and plot feature importances from both the decision tree and random forest.
- Discuss which features are most influential in your model’s decisions.

### 5. Evaluate Using Cross-Validation
- Use scikit-learn’s `cross_val_score` for more robust model evaluation.
- Compare cross-validated results for both classifiers.

---

## Example Libraries

- Python 3.x
- scikit-learn
- matplotlib
- pandas
- numpy
- (Optional) graphviz

## Quick Start

1. **Clone the repo**
   ```bash
   git clone https://github.com/Aiswaryabinu/heart-.git
   cd heart-
   ```
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the notebook or script**
   - Open the included Jupyter notebook or run the Python scripts.

## Contributing

Feel free to submit issues or pull requests to improve this guide or contribute additional examples.

---
