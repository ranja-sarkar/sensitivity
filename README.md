# sensitivity

Selecting a **sample size** for machine learning is a challenging open problem. Typically, there is a relationship between training data size and model performance, especially for nonlinear models. However, the caveat is that such a relation might not exist for some model algorithms and datasets. 

A **sensitivity analysis** forms the basis of testing different model algorithms and their configurations. This helps in evaluating a better algorithm for a task and decide on a rough estimate of the training data size needed to build the predictive model, apart from the statistical heuristics such as number of classes (classification problem), number of input features or the number of hyperparameters that are considered.
<img width="341" alt="1" src="https://github.com/user-attachments/assets/e1ba4eb6-5330-44f4-aaa3-ec492621334d">


A good read on the effectiveness of larger datasets in deep learning models:
https://arxiv.org/abs/1707.02968
