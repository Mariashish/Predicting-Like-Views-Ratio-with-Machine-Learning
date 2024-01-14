# Prediction of Like/Views Ratio for YouTuber MrBeast using Machine Learning

# Introduction:
For this project, I chose to analyze the YouTube channel of the popular YouTuber MrBeast (Jimmy Donaldson) known for extreme generosity and charity projects. The goal was to autonomously create a dataset and build and compare various classification and regression models to predict the Like/Views ratio using machine learning techniques.

# Files Attached:

Dataset: MrBeast400.csv (Contains information on 400 videos)
Jupyter Notebook: ProgettoAIML.ipynb (Includes API Scraping, Descriptive Analysis, Classification, and Regression)
Classification Code: Classificazione10Classi.ipynb
Paper: PaperProgettoAIML_DanieleMariani.pdf

# Project Organization:

### Dataset Creation: Utilized Google API Scraping to gather information from MrBeast's YouTube channel.
Data Cleaning and Feature Engineering: Added new columns like VideoAge(Days), Like/ViewsRatio, Comments/ViewsRatio.
Descriptive Analysis: Explored data through visualizations, including distribution plots, scatter plots, correlation matrix, and word clouds.
### Classification Models: Built and compared models using RandomForest, KNN, Naive Bayes, XGBoost, and SVM with 3 classes (Minimo, Medio, Virale).
Regression Models: Trained and compared Linear Regression, SVR, RandomForest Regression, Lasso Regression, KNN Regression, and XGBoost Regressor.

# Key Findings:
### Classification:

RandomForest and XGBoost outperformed other classifiers.
Naive Bayes showed lower performance.
Models tended to overestimate the Virale class.
Regression:

RandomForest and XGBoost demonstrated superior performance, with lower error dispersion.
SVR showed higher variability and error dispersion.
Conclusion:
The project successfully predicts the Like/Views ratio and provides insights into the YouTube channel's dynamics. RandomForest and XGBoost emerged as top-performing models for both classification and regression tasks.
