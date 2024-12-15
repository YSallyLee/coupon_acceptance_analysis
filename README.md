# In-Vehicle Coupon Acceptance Prediction


### Overview
This project aims to analyze and predict whether a driver will accept an in-vehicle coupon based on various contextual factors, such as demographics, driving conditions, and coupon details. The dataset used for this analysis is sourced from the [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/in-vehicle+coupon+recommendation), originally donated in 2020 and referenced in the paper _"A Bayesian Framework for Learning Rule Sets for Interpretable Classification"_ by Wang et al., 2017. Using various machine learning models and hyperparameter tuning, this project identifies the most effective model for predicting coupon acceptance.”


### Tools and Libraries
* Python: pandas, numpy, matplotlib, seaborn, scikit-learn
* Google Colab for computation

### Key Results
* Best Model: Support Vector Machine (SVM) with an RBF kernel outperformed other models with the best accuracy, precision, recall, F1-score, and lowest MSE.
* Hyperparameters: The best parameters for the SVM model were 𝐶=10 and 𝛾=0.1, achieving a cross-validation score of 0.67458.



### Collaborators
* Shu-Wen Teng
* Yen-Jo Lee

### License
This project is licensed under the MIT License.
