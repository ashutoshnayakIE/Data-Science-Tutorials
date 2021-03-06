# Data-Science-Tutorials
This repository includes short tutorial on specific data science concepts. Although the topics might seem little scattered and random, I came across these topics when working on my research and seemed to me like these are not well covered (in explainable format in forums like medium, you tube as a follow up to the research papers). The links to the tutorials are:

## XGBoost
XGboost is well known machine learning algorithm. XGBoost is famously been used in multiple Kaggle competition winning solutions. While there are a lot of resources on how to implement XGBoost, how to interpret and improve XGBoost models, the following blog talks about how new trees are generated in XGBoost (very similar to boosted trees algorithm). <br>
https://towardsdatascience.com/xgboost-an-intuitive-explanation-88eb32a48eff

## Primer on LIME and Shapley
It is important that our machine learning models are not only performs well in out of sample data, it should be interpretable. LIME and SHAP are two model agnostic models for interpreting machine learning models. There is a lot of tutorial on how to use LIME and SHAP, the following blog is a short tutorial to understanding LIME and SHAP at the lowest conceptual level. <br>
https://towardsdatascience.com/idea-behind-lime-and-shap-b603d35d34eb

## Endogeneity: Why it is important to know the data (3 part blog)
It is extremely important that we know our data, that is what does each predictor variable means. If we know the data, we know what transformations could make sense and even whihc model should we select (for example, if normality assumptions are valid, we can go for OLS, otherwise, we should go for OLD after transformation, if it is a count data, we cannot use OLS but need to poisson regression etc.). Apart from knowing the different predictor variables, we need to know how the data was generated or collected. The data engineering team should know the model based on which coupons were send to the customers, if this information is known, model could be biased. The following three part tutorial provides an introduction to one such issue caused by lack of information of how data was generated: endogeneity, which violates one of the basic principles of causal inference: randomnization.<br>
1) https://towardsdatascience.com/endogeneity-the-reason-why-we-should-know-about-data-part-i-80ec33df66ae
2) https://towardsdatascience.com/endogeneity-the-reason-why-we-should-know-about-data-part-ii-c1487d69aeed
3) https://towardsdatascience.com/endogeneity-the-reason-why-we-should-know-about-data-part-iii-50380e0d996e


## From Information theory to Cross-entropy
Information theory is everywhere with a lot of tutorials on entropy, information etc. But I could not find something that could help me understand why we are using the information theory the way we use it. The following blog is a short walk with history of information theory and how it is connected to one of the most commonly used loss function: cross entropy. <br>
https://towardsdatascience.com/cross-entropy-from-an-information-theory-point-of-view-456b34fd939d


## Akaike information criteria
All of us have used AIC for model selection. This blog is about the idea behind AIC, what is it and why is it used for model selection. While we have been told how to calculate AIC, at least I was never taught the logic behind why are we doing this — this blog aims to cover that.
https://towardsdatascience.com/akaike-information-criteria-942d1f554537
