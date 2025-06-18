# 🗺 Tom's Portfolio

Welcome to my data portfolio! Here, I document a summary of my projects in the data field. 

## 📚 Table of Contents
- [Python](#python)
- [Econometrics](#econometrics)
- [Data Engineering](#data-engineering)
- [SQL](#sql)
- [Tableau](#tableau)

# Python

| Project Link | Area | Project Description | Libraries |    
|---|---|---|---|
|[Telco Customer Churn & Growth Analytics](https://github.com/ThomasTGilham/Churn_Funnel_Analysis_Project_Telco) | Cohort & Retention Analysis, A/B Testing, Churn Prediction (LogReg + RandomForest) | Presents a full analytics pipeline to explore, simulate, and model customer churn using the Telco Customer Churn dataset. The goal is to analyze growth and retention patterns, test strategies to reduce churn, and build a predictive model to identify at-risk customers.| pandas, numpy, matplotlib, seaborn, sklearn (LogReg, Random Forest, metrics), imblearn (SMOTE for class balancing), statsmodels (z-test for A/B testing) |
|[Glassdoor Job Listings Web Scraper](https://github.com/ThomasTGilham/Glassdoor-Job-Listings-Scraper) | Scraping / Big Data | This .ipynb script scrapes job listings from Glassdoor with input for job type, location, and number of jobs to scrape. | Selenium, Chrome Webdriver, BeautifulSoup | 
|[Font Image Classifier](https://github.com/ThomasTGilham/Font_Image_Classifier_ML_CW) | Machine Learning, Convolutional Neural Networks | Built a robust classifier capable of identifying the font of a given text image. This was a multi-class classification task with 2,000–3,000 unique font classes. Achieved test accuracy: 80.19% & AUC: ~0.9998|  Torch, ToTensor, OneCycleLR, pandas, matplotlib |   
|[CS50P](https://github.com/ThomasTGilham/CS50P/blob/main/README.md) | Data Wrangling & EDA | This repo contains the solution to the problem sets in [Harvardx CS50P Introduction to Programming with Python](https://www.edx.org/course/cs50s-introduction-to-programming-with-python). | - |   

***

# Econometrics 

| Project Link | Area | Tools | Project Description | 
|---|---|---|---|
| [VECM Time Series Analysis of S&P 500, CPI, and 3-Month Treasury Bill Rate](https://github.com/ThomasTGilham/Macro_VECM_TimeSeries_Analysis) | Applied Financial Econometrics |R Studio | Conducted a VECM time series analysis of S&P 500 closing prices, CPI index, and 3-month U.S. Treasury Bill rates from 2009 to 2019. It processes and merges monthly data, applies logarithmic transformation, and tests for Stationarity, Structural Breaks, Cointegration, VECM Modelling, & diagnostics checks|
| [Econometric Analysis of Firm Level Productivity](https://github.com/ThomasTGilham/panel-data-OlleyPakesFramework-bootstrap) | Empirical Industrial Organisation | Stata, R Studio | Estimated firm-level productivity using panel data, addressing key econometric challenges including firm heterogeneity, measurement error, endogenous exit, and simultaneity bias|

# Data Engineering

| Project Link | Completion Date | Tools | Project Description | 
|---|---|---|---|
| [Spotify Wrapped](https://github.com/ThomasTGilham/My-Spotify-Wrapped) | June 2025 |Python, PostgreSQL, Airflow, DBT, Docker | Aimed to create a personalized version of Spotify Wrapped, which summarizes a user's listening history for the year. The project used airflow for orchestration, Docker for containerization, dbt for modeling and transforming data, and GitHub Actions for continuous integration and delivery. The goal was to extract the user's listening history data from Spotify's API, transform it, and load it into a database. The transformed data would then be used to generate personalized insights and visualizations summarizing the user's listening history.|
| [Uber Taxi](https://github.com/katiehuangx/data-engineering/tree/main/Uber%20Project) | May 2023 | Python, GCP (Storage, Compute Engine, BigQuery), Mage, Looker Studio | Developed and implemented an end-to-end ETL pipeline for processinsg NYC Trip Record data. The pipeline encompassed extracting raw data, performing data transformation using Python, applying fact and dimensional data modelling techniques, orchestrating the pipeline on Mage, and ultimately creating a dashboard using Looker Studio. |


***

# SQL

| Project Link | Area of Analysis | Project Description | 
|---|---|---|
| [8-Week SQL Challenges](https://github.com/ThomasTGilham/8-Week-SQL-Challenge) | Data analysis, data cleaning, data transformation | This repo serves as the solution for the 8 case studies from the [#8WeekSQLChallenge](https://8weeksqlchallenge.com). It showcases my ability to tackle various SQL challenges and demonstrates my proficiency in SQL query writing and problem-solving skills. | 
| [Health Analytics Case Study](https://github.com/ThomasTGilham/Serious-SQL-Apprenticeship/blob/main/Health%20Analytics%20Mini%20Case%20Study.md) | Health analysis | I answer business questions related to patients data, such as average and median measurements per user, types of measurements for active users, and median blood pressure values for users. |  

***

# Thomas Trainor-Gilham

## PERSONAL PROFILE
##### Highly analytical and results-oriented Data Analyst with a unique blend of expertise in economics, advanced statistical learning, and practical marketing analytics. Proven ability to leverage econometric modeling, time series forecasting, and machine learning techniques to derive actionable insights, optimise marketing spend through Marketing Mix Modeling (MMM), and solve complex business problems. Seeking to apply a robust quantitative skill set and industry experience to impactful data science challenges.

#### Technical Skills: _Python (Scikit-learn, TensorFlow, PyTorch, LightGBM, Selenium) - R - SQL - Relational Data Models - Econometrics - MMM - Forecasting - Data Visualisation (Looker, Tableau)  - Machine Learning - Big Data - Web Scraping - GA4 -  Segmentation - AWS_

## WORK EXPERIENCE
### Academic Researcher | IBM 
#### London, UK | Jan 2024 - Present
* Coauthor of working title: “Bridging the Skills Gap: Strategic Insights for IBM’s Workforce of the Future" in which I utilised econometric modelling, forecasting, & classification techniques to quantify & predict AI's impact on workforce tasks and the UK labour market.
* Scraped and cleaned job listings and interview reviews data from the web using Selenium and conducted unsupervised NLP analysis on scraped data using TF-IDF vectorisation, K-Means clustering, and LDA topic modeling to identify emerging skill patterns and thematic job clusters.
* Preprocessed and visualised large-scale text data with spaCy and scikit-learn, applying dimensionality reduction (t-SNE/UMAP) and word-frequency insights to best guide skills education strategy for the future workforce. 

### Data Analyst | MullenLowe Group
#### London, UK | Dec 2022 - Nov 2024
* Implemented Marketing Mix Modeling (MMM) to quantify the effectiveness and ROI of diverse marketing channels (e.g., TV, digital, print) for major accounts including Co-op, Bupa, and Harley Davidson.
* Developed a Gradient Boosting Decision Trees age inference model (LightGBM-based) using GA4 data to predict customer age segments based on behavioural features (e.g. spend patterns, time-of-day preferences, brand loyalty).
* Enabled personalised targeting of that segment, contributing to a +16% YoY uplift in 18–30 year old Co-op membership registrations.
* Leveraged model outputs to inform segmentation, campaign design A/B testing, and geo-targeting strategies tailored to younger customer cohorts to optimise client advertising spend and improve campaign effectiveness.
* Partnered with marketing, media  & client stakeholders to translate & present findings into actionable business strategies.

### Retail Analytics Consultant | Kantar Consulting
#### London, UK | Dec 2021 - Dec 2022
* Worked in Kantar’s Perfect Category division delivering range, space, and pricing optimisation for FMCG clients (Colgate-Palmolive, Unilever, Red Bull, etc) using EPoS, panel, and shopper behaviour data from retailers across EMEA.
* Applied advanced analytics with Python (TURF, clustering, price elasticity, promotion uplift modelling) to inform category strategies and drive incremental growth.
* Built and presented data-driven recommendations on assortment, shelf layout, and shopper targeting to senior client stakeholders across sales, marketing, and category management.

## EDUCATION & COURSES
### MSc Economics with Data Science | University of Bristol
#### Bristol, UK	| Sep 2024 - Present
* Empirical Industrial Organisation: (100% Achieved); Production/demand functions, Maximum Likelihood Estimators, & entry games.
* Machine Learning: (90%); LDA, QDA, KNN, cross-validation, regularisation, PCA, Random Forests, Boosting, SVMs, neural networks.
* Applied Financial Econometrics: (77% Achieved); Stationarity, threshold models, ARMA, VAR, VECM, cointegration, ARCH / GARCH
* Large Scale Data Engineering: (85% Achieved); AWS cloud architecture best practices, cloud economics, Hadoop, Apache Spark, DevOps

### BSc Economics | University of Bristol
#### Bristol, UK | Sep 2018 - June 2021
* Achieved First-class Honours (72%) with chosen modules  heavily focused on Econometrics, Microeconomics, and statistics.

### The Complete dbt (Data Build Tool) Bootcamp: Zero to Hero
#### Udemy | May 2025
### AWS Certified Cloud Practitioner
#### Amazon Web Services | Dec 2024
