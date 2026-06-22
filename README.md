# Electromagnetic-Induction-Prediction-using-Machine-Learning

A physics‑informed machine learning system that simulates electromagnetic induction, generates synthetic data, and predicts induced EMF with near‑perfect accuracy.

**OVERVIEW**

This project bridges classical electromagnetism and modern machine learning in a single, production‑quality Jupyter Notebook. It implements Faraday’s Law of Induction to generate 10,000 realistic synthetic samples, performs detailed exploratory data analysis, engineers domain‑aware features, and trains four regression models to predict the induced electromotive force (EMF).

The result: R² = 1.0 across all models, proving that physics can be perfectly learned from data – and that combining domain knowledge with ML yields interpretable, robust systems.

**PHYSICS FOUNDATION**

Faraday’s Law: EMF = -N * dΦ/dt

EMF : induced voltage (Volts)

N : number of coil turns

Φ = B * A * cos(θ) : magnetic flux (Weber)

dΦ/dt : rate of change of flux

Lenz’s Law – the negative sign indicates that the induced current opposes the change in flux.

**Applications:** electric generators, transformers, wind turbines, electric motors.

**FEATURES**

Physics Simulation – modular, well‑commented functions that mimic real coil‑magnet dynamics

Synthetic Dataset – 10,000+ samples with 8 input features and target EMF, saved as CSV

Exploratory Data Analysis – scatter plots, histograms, and time‑domain curves using Matplotlib, Seaborn, and Plotly

Feature Engineering – physics‑based features (flux magnitude, turn density) to aid tree‑based models

**Machine Learning Pipeline – standard scaling, train/test split, four regression models:**

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

Model Evaluation – MAE, MSE, RMSE, R² comparison; all achieve near‑zero error

Interactive Prediction Tool – input coil & field parameters via sliders, get instant EMF prediction (ML) and exact physics value

Animated Visualisation – rotating coil and live voltage waveform (Plotly animation)

Professional Write‑up – comprehensive discussion of physics‑AI synergy and simulation vs. real‑world measurements

**TECHNOLOGIES USED**

Core: Python, NumPy, Pandas
Visualisation: Matplotlib, Seaborn, Plotly
Machine Learning: Scikit‑learn (Linear Regression, Trees, Ensemble methods)
Interactivity: ipywidgets, Plotly widgets
Development: Jupyter Notebook, Git, GitHub
