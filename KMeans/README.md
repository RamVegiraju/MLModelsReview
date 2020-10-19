# **Pros/Cons for Model**

## **Pros**

- Very easy to **interpret** the results and highlighting conclusions in a visual manner.
- Very flexible and fast, also **scalable** for large datasets.
- Always yields a result.

## **Cons**

- Struggles with a **high number of dimensions**, need to use PCA or spectral clustering to help fix issue.
- Choosing **K value** manually/based off of your domain knowledge of the problem. Need to use **elbow method** to assess best K value.
- Sensitive to **outliers.**
- Sensitive to **initialization**, if the initial centroids you pick are inaccurate this can cause problems with later points.
