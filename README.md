# Fairness in Machine Learning

This repository contains a Jupyter Notebook that demonstrates how to evaluate and mitigate bias in machine learning models using the Iris dataset and synthetic data. The notebook uses various fairness metrics and techniques to ensure that the model treats different groups fairly.

## Requirements

- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-learn
- Fairlearn
- Matplotlib
- 
## Fairness Metrics

- **Demographic Parity**: Measures whether different groups have similar positive prediction rates.
- **Equalized Odds**: Measures the differences in True Positive Rates (TPR) and False Positive Rates (FPR) between groups.
- **Disparate Impact**: Ratio of positive rates between groups.
- **Equal Opportunity**: Difference in TPR between groups.
- **Predictive Parity**: Difference in precision between groups.

## Mitigating Bias

The notebook demonstrates how to use the `ExponentiatedGradient` method from the Fairlearn library to mitigate bias in the model.

## Results

The notebook provides detailed results on the accuracy and fairness metrics before and after bias mitigation.

