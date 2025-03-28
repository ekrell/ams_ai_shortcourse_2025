# Intermediate Machine Learning in Python for Environmental Science Problems

A one-day short course presented at the [American Meteorological Society (AMS) Annual Meeting 2025](https://annual.ametsoc.org/index.cfm/2025/)

- New Orleans Ernest N. Morial Convention Center
- January 12, 2025 at 8:00 AM - 3:30 PM Central Time (Hybrid)
- [Course Registration](https://www.ametsoc.org/index.cfm/ams/education-careers/careers/professional-development/short-courses/intermediate-machine-learning-in-python-for-environmental-science-problems-2025/)

## Course Description

The major goal of this course is to help participants better apply ML for environmental science applications. Instead of focusing deeply on specific ML architectures, we are providing material that will be broadly useful across many environmental ML applications. With the rapid development of ML techniques, it is important for practitioners to be able to appropriately tailor these models for complex environmental applications which often use datasets that are high-dimensional and highly imbalanced.

ML model training tends to be very sensitive to the choice of hyperparameters. Beginner tutorials usually demonstrate tuning these with a simple grid search, if they demonstrate hyperparameter tuning at all. For complex environmental models, that grid search may be too computationally intensive. Here, we will demonstrate how to use packages for automatic hyperparameter tuning, and offer practical guidance on which tuning strategies are appropriate for different situations.

Another major concern is model evaluation. Using conventional metrics like accuracy and mean squared error, it is very easy to be misled regarding model performance. Here, we will demonstrate model evaluation with a variety of forecasting skill scores that are much better for capturing how the model performs for critical events instead of average performance. This is a major concern for meteorology where a model can have very high average performance, but fail to predict the extreme events (e.g. storms). In addition, we will demonstrate how to create and interpret evaluation graphics such as the receiver operating characteristic curve for a deeper understanding of model performance.

Imbalanced datasets are a major concern for ML modeling in environmental science. Very often, it is the rare events that we are most interested in predicting and where model performance is most critical. We will demonstrate several strategies for working with imbalanced datasets that can potentially improve model performance. These include sampling techniques as well as methods for generating synthetic examples of the minority class. We will also share some of the caveats and potential pitfalls associated with the methods.

Finally, we will discuss model interpretation through explainable AI (XAI) techniques. There are many reasons why users want to understand how their model works. XAI may reveal failure cases that could lead to ideas for improving the model. Or, the model may reveal that it has learned physically-realistic strategies which may help us trust the models more for use in critical situations. We will introduce XAI and demonstrate several commonly used methods. We will show how XAI can be used to investigate interesting cases in imbalanced datasets. We will also show examples of some of XAI pitfalls and how to avoid being misled by the explanations.

## Authors

- [Evan Krell](https://ekrell.github.io/), `evankrell730@gmail.com`
- [Kara D. Lamb](https://kdlamb.github.io/), `kl3231@columbia.edu`
- Praveen Singh, `praveen.singh@noaa.gov`
- [Christian Duff](https://www.linkedin.com/in/christian-duff-898103211/), `cduff4@islander.tamucc.edu`

## Agenda

| **Topic**     |  **Materials**                                               | **Instructor**  |
|---------------| -------------------------------------------------------------|-----------------|
| Introduction |  [slides](AMSAI2025_Intro.pdf)                                | Evan Krell      |
| Imbalanced data | [notebook](AMSAI2025_DataBalance.ipynb)                    | Praveen Singh   |
| Hyperparameter tuning | [notebook](AMSAI2025_HyperparameterTuning.ipynb)     | Christian Duff  | 
| Model evaluation | [notebook](AMSAI2025_Evaluation.ipynb)                    | Evan Krell      |
| Explainable AI | [notebook](AMSAI2025_XAI.ipynb)                             | Evan Krell      | 
| Physics-informed ML | [notebook](AMSAI2025_physicsai.ipynb)                  | Kara D. Lamb    | 
| Small groups exercise | [notebook](AMSAI2025_Exercise.ipynb)                 | Everyone        | 

