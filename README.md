Introduction to machine learning and data mining
Project
🧠 South African Heart Disease Data Analysis

This repository presents an in-depth analysis of the South African Heart Disease dataset, exploring how various risk factors contribute to coronary heart disease (CHD). The project combines machine learning, statistical analysis, and data visualization to investigate data structure, correlations, and predictive potential.

📊 Project Overview

Dataset: Subset of the CORIS study (Rousseauw et al., 1983), including 462 individuals and 10 health-related attributes.

Objective: Identify significant CHD predictors and evaluate whether linear dimensionality reduction (PCA) can capture discriminative patterns between healthy and CHD-affected individuals.

🔬 Methods & Workflow

Data Preprocessing – Standardization, outlier removal, and normalization to address variable scale imbalance.

Exploratory Data Analysis (EDA) – Statistical summaries, boxplots, and correlation heatmaps to visualize relationships.

Dimensionality Reduction (PCA) – Performed using Singular Value Decomposition (SVD) to retain 90% of data variance.

Model Evaluation – Comparison between raw and standardized PCA projections; assessment of variance explained and component significance.

📈 Findings

Standardization was critical due to large variance differences across features.

PCA alone was insufficient for accurate CHD classification, as clusters between classes overlapped heavily.

Insights point toward Logistic Regression or nonlinear ML models (e.g., Random Forests, SVM) for improved performance.

⚙️ Skills Demonstrated

Data preprocessing and feature scaling

Exploratory data visualization

Principal Component Analysis (PCA)

Model evaluation and variance analysis

Scientific communication and reporting

🧩 Technologies

Python, NumPy, Pandas, Matplotlib, scikit-learn

Group 5
Authors:

Aleksander Nagaj
Davide Ventuo
Filippo Bosi
Dataset
South african heart disease
