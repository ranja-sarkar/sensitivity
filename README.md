
Selecting a **sample size** for machine learning is a challenging open problem. Typically, there is a relationship between training data size and model performance, especially for nonlinear models. Apparently the caveat is that such a relation might not exist for some model algorithms and datasets. 

Substack article on tests & their statistical power: https://open.substack.com/pub/ranjas/p/power-analysis-24-02-02

A **sensitivity analysis** forms the basis of testing different model algorithms and their configurations with the data sizes used to train them. This helps in evaluating a better algorithm for a task and decide on a rough estimate of the training data size needed to build an optimally performing predictive model, apart from statistical heuristics such as number of classes (for classification), number of input features or number of hyperparameters that are considered for the model.
<img width="341" alt="1" src="https://github.com/user-attachments/assets/e1ba4eb6-5330-44f4-aaa3-ec492621334d">


Analysing power and sensitivity with examples: https://github.com/ranja-sarkar/power-sensitivity/blob/main/notebooks/sensitivity_analysis.ipynb

A good read on the **effectiveness of bigger dataset size in deep learning**:
https://www.semanticscholar.org/reader/8760bc7631c0cb04e7138254e9fd6451b7def8ca

