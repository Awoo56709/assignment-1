# Homework 1 Task 3

---

Answer the following questions based on exercises from *An Introduction to Statistical Learning with Applications in Python*.

## Chapter 2.4 Exercises

---

### Exercise 1 (ISLP exercise 2)

Explain whether each scenario is a **classification or regression** problem, and indicate whether we are most interested in **inference or prediction**. Finally, provide **n** (size of observation dataset) and **p** (number of predictors).

**(a)**  We collect data on 200 protected marine reserves worldwide. For each reserve we record species richness, reserve size, years since establishment, enforcement budget, and proximity to human settlements. We are interested in understanding which factors affect species richness.

> **This would be a regression problem as we want to understand the factors that affect species richness (quantitative). Because of this, the goal of this would be inference as mentioned and that we want to understand what underlying factors affect species richness. The number of observation equals 200 reserves and the number of predictors is 4. **

---

**(b)** A conservation agency wants to know whether a proposed habitat corridor will successfully support wildlife movement or fail to do so. They collect data on 30 previously established corridors. For each corridor they have recorded whether wildlife movement was successful or unsuccessful, corridor width, length, surrounding land use type, and eight other variables.

> ** This would be a classification problem as the outcome is binary (failure or success) and categorical. The goal of this problem is prediction as the agency wants to know whether the proposed habitat corridor will be successful. The number of the observations is 30 and the number of predictors is 11. **

---

**(c)** We are interested in predicting weekly average ground-level ozone concentration in a coastal city. We collect weekly data for all of 2019. For each week we record average ozone concentration, sea surface temperature, wind speed, solar radiation, and atmospheric

> **This would be a regression problem as ozone concentrations are continuous rather than a binary outcome. The goal of this problem would be prediction or forcasting ozone levels based on environmental variables. The number of observations is 52 observations (1 observation per week in a year) and there are 4 predictors. **

---

### Exercise 2 (ISLP exercise 5)

What are the advantages and disadvantages of a very flexible (versus a a less flexible) approach for regression? Under what circumstances might a more flexible approach be preferred to a less flexible approach? When might a less flexible approach be preferred?

> **A very flexible approach for regressions can adapt complex and non-linear relationships due to less assumptions being made about the functional form of f and achieve a lower test MSE and less bias. The disadvantages of this approach is that they may overfit the data, they require more data and may be harder to interpret for inference. Less flexible approaches, like a linear regression, assumes a simple functional form of f. The advantages of this approach are that they are easier to interpret, require fewer parameters, and require a smaller amount of data. The disadvantage would that if the true relationship is nonlinear, a less flexible model may underfit the data and produce biased predictions. This leads to the idea that a flexible approach may be preferred when prediction accuracy is prioritized and enough data is available. A less flexible approach would be ideal when interpretability, simplicity or limited data make a more restrictive model more approapriate. **

---

### Exercise 3 (ISLP exercise 6)

Describe the differences between a **parametric** and a **non-parametric** statistical learning approach. What are the **advantages** of a parametric approach to regression or classification (as opposed to a non-parametric approach)? What are its **disadvantages**?

> ** The parametric approach assumes a specific functional form or shape for the relationship between the predictors and response. The pros of this approach is that they are simpler, make it computationally easier to estimate a few parameters, easier to make an inference and work well with training data sets. The disadvantages of these models arer they may be far off from the true function as they are too simple, thus making predictions possibly less accurate. Non-parametric approaches do not assume a fixed function and lets the data determine the shape of the function. Moreover, they are more flexible in that they can capture more complex and non-linear patterns. This goes to say that they may be better at prediction. However, the disadvantages include requiring a lot more data, can overfit models    - following noise- and can be less interpretable than parametric or more flexible models. **



