# DataScience-to-Medium-with-ChatGPT4

This repository documents a complete data science workflow using popular Kaggle datasets, powered by OpenAI's ChatGPT-4 code interpreter. It showcases the steps of a data science project, including data cleaning, exploratory data analysis (EDA), feature engineering, model building (with a focus on deep learning), and publishing insights on Medium.

All the code in this repository was generated using ChatGPT-4, and the entire chat transcript of the project is available as a PDF file: **ChatGPT-Colab-Mental Health in Tech.pdf**, included in this repository.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Data Science Workflow](#data-science-workflow)
  - [1. Data Cleaning](#1-data-cleaning)
  - [2. Exploratory Data Analysis (EDA)](#2-exploratory-data-analysis-eda)
  - [3. Feature Engineering](#3-feature-engineering)
  - [4. Model Building](#4-model-building)
  - [5. Model Evaluation](#5-model-evaluation)
- [Medium Article](#medium-article)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

In this project, we analyze a Kaggle dataset related to mental health in the tech industry, following the CRISP-DM methodology. This process includes data understanding, preparation, modeling, and evaluation. The insights from the project were published in a Medium article.

The **entire code and analysis** for this project were generated using ChatGPT-4. You can find the complete transcript of the chat sessions used to generate the code in the file **ChatGPT-Colab-Mental Health in Tech.pdf**.

## Dataset

The dataset used in this project comes from Kaggle. It consists of a survey dataset focusing on **mental health in the tech industry**, with responses related to demographics, mental health history, and work-related factors.

- **Source**: [Kaggle Datasets](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey)

## Data Science Workflow

This project follows a structured data science workflow:

### 1. Data Cleaning
Initial cleaning processes were performed, including handling missing values, removing irrelevant columns, and standardizing the data.

### 2. Exploratory Data Analysis (EDA)
EDA techniques were applied to identify key patterns in the dataset, such as distributions of age and gender, and correlations between mental health and work environment factors.

### 3. Feature Engineering
Features were selected and engineered to enhance model performance. Categorical variables were label-encoded, and numerical values were scaled to prepare for machine learning models.

### 4. Model Building
Several machine learning models were built, including clustering algorithms like K-Means, DBSCAN, Hierarchical Clustering, and Gaussian Mixture Models. The K-Means algorithm was identified as the best-performing method for clustering.

### 5. Model Evaluation
The models were evaluated using internal clustering metrics like **Silhouette Score**, **Davies-Bouldin Index**, and **Calinski-Harabasz Index**. K-Means performed the best overall and was used for further analysis.

## Medium Article

The insights derived from this analysis are documented in the Medium article: [Mental Health in Tech: A Data-Driven Approach Inspired by Real-Life Events](https://medium.com/@apurva.karne/mental-health-in-tech-a-data-driven-approach-inspired-by-real-life-events-638efa3a9462).

This article explores how various factors in the tech industry contribute to mental health challenges and provides recommendations based on data-driven insights.

### Youtube Video(https://youtu.be/w8lzxp9EcBY) 

## Technologies Used

- **Python**: Data manipulation and analysis
- **Pandas**: Data processing and manipulation
- **Seaborn & Matplotlib**: Data visualization
- **Scikit-learn**: Machine learning algorithms
- **ChatGPT-4**: Code generation and workflow automation
- **Google Colab**: Cloud-based Jupyter notebooks for running the code

## Contribution

This project is part of an academic assignment. While it's not open for direct contributions, feedback and suggestions are welcome through the issue tracker.
