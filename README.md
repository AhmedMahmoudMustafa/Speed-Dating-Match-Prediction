# Speed Dating Recommendation System

## Problem Formulation:

### Input:
The dataset comprises detailed information about participants in speed dating events, encompassing personal details, survey responses, partner information, and post-event feedback.

### Output:
The objective is to predict the probability (0-1) of a successful match in a speed dating session.

### Data Mining Function:
Binary classification is employed to determine the likelihood of a successful match.

### Challenges:
1. **Missing Values:** Develop a strategy for handling missing data.
2. **Class Imbalance:** Address the imbalance between matched and unmatched instances.
3. **Hyperparameter Tuning:** Optimize the model's performance through systematic hyperparameter search.

## Impact:
The recommendation system aims to enhance the speed dating experience, providing more successful matches and increasing participant satisfaction.

## Ideal Solution:
A robust predictive model that accurately identifies the probability of a successful match, leveraging a well-defined feature set and effective preprocessing techniques.

---

# Model Tuning and Documentation

## Trial 0: Random Forest
- **Observations:** Achieved a best score of 85.36%. Identified optimal hyperparameters.

## Trial 1: Decision Tree
- **Observations:** Achieved a best score of 81.55%. Identified optimal hyperparameters.

## Trial 2: Bayesian Search - XGBoost
- **Observations:** Achieved a best score of 87.73%. Bayesian search demonstrated superior performance.

## Trial 3: Random Search - Decision Tree
- **Observations:** Achieved a best score of 81.59%. Random search performed comparably to grid search.

## Trial 4: XGBoost - Second Iteration
- **Observations:** Achieved a best score of 87.51%. Refined hyperparameters for improved performance.

---

# Conclusion

- Explored different models and hyperparameter tuning methods.
- Bayesian search with XGBoost showed the highest performance.
- The process documented for reproducibility and future reference.
