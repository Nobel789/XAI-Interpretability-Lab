# XAI-Interpretability-Lab
This repository contains a suite of techniques for inspecting and interpreting machine learning models. The goal is to move beyond "black box" predictions and understand the underlying logic of both traditional and deep learning architectures.

Explainable AI (XAI) Code Demos
This repository contains a suite of techniques for inspecting and interpreting machine learning models. The goal is to move beyond "black box" predictions and understand the underlying logic of both traditional and deep learning architectures.

🏗️ Project Components
🌍 Global and Counterfactual Explanations
Global Interpretability: Implementation of Partial Dependence Plots and ALE Plots to interpret Random Forest behavior.

Counterfactuals: Simulating "what-if" scenarios by finding the smallest change to input features that results in a different model outcome.

🔎 Deep Learning & Latent Space
GAN Dissection: Techniques for inspecting layers and interpreting the function of specific units within Generative Adversarial Networks.

Embedding Visualization: Dimensionality reduction using PCA, t-SNE, and UMAP to make high-dimensional latent spaces meaningful and interpretable.

### ⚖️ Responsible AI & Fairness
* **Bias Auditing**: A comprehensive framework using **Fairlearn** to detect representation bias in training data and disparaties in model performance across sensitive groups (e.g., Age, Gender).

### 📉 Transparent Modeling
* **Regression Interpretability**: Visualizing the impact of **Lasso** and **Ridge** regularization paths to understand feature selection stability.
* **RuleFit**: Implementing hybrid models that combine linear regression with decision rules to capture non-linear interactions while remaining human-readable.
