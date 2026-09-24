Project Overview & Brief Overview

I developed this project as part of the AICTE | IBM SkillsBuild Data Analytics with AI Internship. I applied exploratory data analysis (EDA) and a supervised machine learning classification pipeline to examine catalog structures and distribution patterns using the Netflix Movies and TV Shows dataset.

Link to Dataset
Kaggle Dataset Source Link: https://www.kaggle.com/datasets/shivamb/netflix-shows

Project Description

I analyzed the streaming content ecosystem by evaluating temporal release trends, production countries, and age ratings. By engineering descriptive metadata features, I trained a supervised Random Forest classification model to accurately categorize catalog media as either Movies or TV Shows.

Technologies Used

Programming Language: Python
Environment: Jupyter Notebook / JupyterLite
Data Processing & ML Libraries:
pandas==2.2.0
numpy==1.26.4
matplotlib==3.8.3
scikit-learn==1.4.1

Setup and Run Instructions

Install all required dependencies by running:
pip install -r requirements.txt
Ensure the dataset file (netflix_titles.csv) is placed in the working directory.
Open Sangeeth_NetflixAnalytics.ipynb in the Jupyter environment and execute the cells sequentially to run data ingestion, preprocessing, visualizations, and model training.

Key Information

Dataset Scope: Contains 8,807 total records across 12 descriptive attributes (type, title, director, country, release_year, rating, duration, listed_in, etc.).
Catalog Distribution: Movies make up roughly 70% of the overall catalog, while TV Shows comprise the remaining 30%.
Temporal Growth Trends: Content production experienced an aggressive upward surge, peaking heavily in the post-2015 era.
Feature Engineering & Preprocessing: Missing values handled via placeholder imputation (Unknown / Not Rated), target encoding applied using binary labels, and categorical features transformed via LabelEncoder.
Model Performance Metrics: The Random Forest Classifier (n_estimators=100) achieved a robust test accuracy of 74.33%, validated through standard classification metrics (precision, recall, and F1-scores).
