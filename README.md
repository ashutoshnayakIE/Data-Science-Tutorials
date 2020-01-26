# Data-Science-Tutorials
This repository includes short tutorial on specific data science concepts. Although the topics might seem little scattered and random, I came across these topics when working on my research and seemed to me like these are not well covered (in explainable format in forums like medium, you tube as a follow up to the research papers). The links to the tutorials are:

## XGBoost
XGboost is well known machine learning algorithm. XGBoost is famously been used in multiple Kaggle competition winning solutions. While there are a lot of resources on how to implement XGBoost, how to interpret and improve XGBoost models, the following blog talks about how new trees are generated in XGBoost (very similar to boosted trees algorithm). 
https://towardsdatascience.com/xgboost-an-intuitive-explanation-88eb32a48eff

## A/B Testing
This is a theoretical guide with an interactive toy example for AB testing (split testing). We go through different topics of A/B testing -- how to choose the metrics, design the experiments and analyze the results after running the experiments. We also cover some statistical background required for A/B testing. We build an interactive toy example to learn how to analyze results from A/B testing.
The different topics we cover in this project are below. The toy example is built along with the theoretical background.
1. Introduction
2. Statistical Background
3. Selecting the Metrics for A/B Testing
4. Designing the Experiment
5. Analyzing results
6. Bayesian approch to A/B Testing
7. Profit maximizing of A/B Testing (Marketing Science article)
https://github.com/ashutoshnayakIE/ABTesting

## Thompson Sampling
A tutorial explaining what is Thompson sampling, how it is different from greedy and $\epsilon$-greedy algorithm and how it can be 
implemented. We also show a small toy example for understanding how Thompson samplling is different from greedy-algorithm. It is python notebook where you can go through the theoretical foundations along with the code.
https://github.com/ashutoshnayakIE/RL/blob/master/ThompsonSampling.ipynb

## Hyper-parameter Optimization
Hyper-parameter optimizatio in important when the optimization function is very complex (example complex Machine learning algorithms).
This is a tutorial on hyper-parameter example with a toy problem using hyperOpt. It explains what are we doing when we say hyper-paramete optimization. We also show an example its implementation in python. After this tutorial, you should be able to implement bayesian optimization procedure along with understanding the theoretical background for it.
https://github.com/ashutoshnayakIE/hyper_parameter_optimization

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
