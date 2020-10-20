# **Pros/Cons**

## Pros

- A **lazy-learning algorithm**, no actual training step, new data is simply tagged to a majority class, based on historical data. Very easy to understand and implement.
- Can be used for **both** classification and regression.
- Only one **hyper-parameter**: k value.
- **Non-parametric**, makes no assumptions about the data/parameters
    - Parametric: Assume statistical distributions in the data, several conditions need to be met (Ex: Linear Regression)
    - Non-Parametric: Makes no assumptions about data distribution/conditions for the data to meet.

## Cons

- Struggles with **large number of dimensions**, the greater the number of dimensions the harder for the algorithm to efficiently calculate distance (**Curse of Dimensionality)**.
    - Often need to use dimensionality reduction techniques, especially in regression tasks with noisy data
- Very **sensitive to outliers & noise**
- Can become very **computationally expensive** as the **dataset grows**, need a lot of memory and can become very slow with a large sized dataset
- **K value selection**, often need to estimate ranges or combine with cross-validation techniques to obtain the optimal k value selection
    - Frequent technique is to plot an **elbow graph** to find optimal k value
