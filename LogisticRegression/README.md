# **Model Theory & Pros/Cons**

## Pros

- **Simple algorithm** that is easy to implement, does not require **high computation power**.
- Performs extremely well when the data/response variable is **linearly separable**.
- Less prone to over-fitting, with **low-dimensional data**.
- Very easy to **interpret**, can give a measure of how **relevant a predictor** is and the **association** (positive or negative impact on response variable).

## Cons

- Logistic regression has a **linear decision surface** that separates its classes in its predictions, in the real world it is extremely rare that you will have linearly separable data.
- Need to perform careful data exploration, logistic regression suffers with datasets with **high multicollinearity between their variables**, repetition of information can lead to **wrong training of parameters**.
- Requires that **independent variables are linearly related to the log odds (log(p/(1-p)).**
- Algorithm is **sensitive to outliers**.
- Hard to **capture complex relationships,** deep learning and classifiers such as Random Forest can outperform with more realistic datasets.
