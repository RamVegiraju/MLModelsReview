# **Pros/Cons Multiple Linear Regression**

##Pros

- Easy to implement, theory is not complex, **low computational power** compared to other algorithms.
- Easy to **interpret coefficients** for analysis.
- Perfect for **linearly separable datasets**.
- Susceptible to **overfitting**, but can avoid using dimensionality reduction techniques, cross-validation, and regularization methods.

##Cons

- Unlikely in the real world to have perfectly linearly separable datasets, model often **underfits** in real-word scenarios or is outperformed by other ML and Deep Learning algorithms.
- **Parametric**, has a lot of assumptions that needs to be met for its data in regards to its distribution. Assumes a **linear relationship** between the dependent and independent variables.
    - Parametric: Assume statistical distributions in the data, several conditions need to be met (Ex: Linear Regression)
        - **Examples of Assumptions**
            - There is a linear relationship between the dependent variable and the independent variables.
            - The independent variables aren’t too highly correlated with each other.
            - Your observations for the dependent variable are selected independently and at random.
            - Regression residuals are normally distributed.
    - Non-Parametric: Makes no assumptions about data distribution/conditions for the data to meet.
