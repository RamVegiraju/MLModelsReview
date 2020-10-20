# **Model Theory & Pros/Cons**

## Pros

- **Speed**, assumptions of feature independence allows the algorithm to be very fast. If this assumption holds true, performs exceptionally well.
- Performs well with **multi-class prediction**
- Works well with **high dimensions,** works well with problems such as text classification (spam detection in the code demo)

## Cons

- Assumes **all features are independent**, this is rarely accurate in real life.
- **Zero Frequency**: If the categorical variable has a category in the test data set, which was not observed in the training data set, the model assigns a zero probability to this category and fails at making a prediction. Use **smoothing** to deal with this issue.
    - Smoothing is a technique in detecting trends with noisy data for cases where the shape of the trend is unknown. **Laplace Smoothing** is commong with Naive Bayes, it is used with categorical data and meant to allevaite the problem of zero probability. Attaching an additional link in bullet below about smoothing in relation to Naive Bayes.
    - [https://towardsdatascience.com/introduction-to-naïve-bayes-classifier-fa59e3e24aaf](https://towardsdatascience.com/introduction-to-na%C3%AFve-bayes-classifier-fa59e3e24aaf)

