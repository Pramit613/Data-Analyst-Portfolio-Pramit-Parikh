# Data Analyst Portfolio - Pramit Parikh

## About - 
My name is Pramit Parikh and I am a Data Analyst with a proven track record of success in data-driven decision making and problem-solving. I have extensive experience in using data to identify patterns, trends, and insights in order to make informed decisions. I am highly proficient in data visualization, data analysis, data wrangling, and statistical analysis. My portfolio showcases my data management and analysis skills, which I have acquired through a combination of formal education, professional experience, and self-teaching.

## What Have I Done?
My portfolio includes a range of projects that I have completed over the years and most of them come from my post-graduate degree in Data Analytics for Business from St. Clair College in Canada. These projects range from simple data visualization tasks to complex data wrangling and machine learning tasks. For each of these projects, I have provided a brief description of the work that I have completed and the tools I used to complete them. These projects cover multiple fields such as marketing, healthcare, project management, finance and machine learning. My portfolio also includes my skills in data mining and predictive analytics. This includes the algorithms and techniques I have used to build models and gain insights from multiple data sets.

Tips: For data science projects with python, I would recomend you to install numpy , pandas , scipy , scikit learn , matplotlib , seaborn thest basic libraries.

## Table of Contents
- [About](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh#about)
- [Portfolio Projects](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh#all-my-work-sorted-by-most-recent)
  - [Projects based on Marketing Analysis](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh#all-marketing-analytics-projects)
    - [Twitter Airline Tweets Sentimental Analysis](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh#4-twitter-airline-tweets-sentimental-analysis)
    - [Mobile Apps Behvioural Analysis](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh#3-mobile-apps-behvioural-analysis)
    - [Customer Segmentation on App Usage](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh#2-customer-segmentation-on-app-usage)
    - [Churn Prediction Analysis on Telecommunication](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh/tree/main/All%20Marketing%20Projects/Churn%20Prediction%20Analysis)
  - [Projects based on Healthcare Analysis](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh#projects-based-on-healthcare-analysis)
  - [Projects based on Hotel Booking Analysis](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh#project-based-on-hotel-booking-analysis)
  - [Projects Management](https://github.com/DevkumarPatel21/data-analyst-portfolio#project-management-project)
- [Certificates](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh#certificates)

## All My Work (Sorted By Most Recent)
Here I have listed all the my data analytics projects, along with the technology stack that was utilised to resolve the issues.

## All Marketing Analytics Projects 

This portfolio showcases a collection of marketing analytics projects I have completed at various stages of my career. Each project has been chosen to demonstrate my technical expertise in a variety of analytics methods and tools used in the marketing analysis world, including churn prection analysis, customer segementation analysis, sentimnetal analysis using Natural language processing and also product and customer behaviour analysis. My goal with this portfolio is to provide an overview of my work and to demonstrate the potential of leveraging data-driven insights to improve marketing performance and profitability.

***All detailed explanation of the project with respect to code and necessary recommendaions is given in the python file link, which has been provided in each section.***

Finally, I have also included a selection of the data sets that I have worked with over the years. This includes both public and private data sets, as well as datasets that I have created myself.

## 1. Twitter Airline Tweets Sentimental Analysis
**Code:**[Project-Twitter-Tweets-Sentimental-Analysis.ipynb](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh/blob/main/All%20Marketing%20Projects/Twitter%20Sentiment%20Analysis/Project-Twitter-Tweets-Sentimental-Analysis.ipynb)

**Description:** The dataset contains 14,640 records with 15 attributes related to Twitter data. It focuses specifically on the comments made by passengers about airlines and their services. Airlines such as US Airways, America, Southwest, Delta, Virgin America, United, and US Airways are included. To identify the emotions of customers regarding the airlines, a sentiment analysis was conducted. The sentiment of the tweets was labeled as 'airline_sentiment' with categories of 'positive', 'negative', and 'neutral'. The project consists of the following steps: loading data, cleaning and preprocessing, filling in missing values, exploratory data analysis (EDA), plotting pie-charts, histograms, transforming sentiments into binary, implementing models, and extracting features.

**Skills:**  Data cleaning, Data preprocessing, Data insights, Data visualization, Feature Engineering, Model Building, Feature Extraction,Term frequency-inverse document frequency (TF-IDF).

**Technology:** Python, Pandas, Numpy, Scipy, Seaborn, Matplotlib, Nltk, nltk.stopwors, corpus, importing models, TF-IDF Vectorizer.

**Models:** Naive Bayes Model, KNN, Support Vector Machine, Decision Tree Model and Random Forest.

**Result:** In this project, two features are of paramount importance: text and airline_sentiment. I removed stopwords from the comments in order to eliminate common English words. I then created a corpus, which is a collection of words, and I performed feature extraction methods such as Count Vectorizer and TF-IDF Vectorizer before the sentiment was encoded using a label encoder. Afterward, I tested all models with both vectorizers and was able to compare the best model to prove the authenticity of the results.

## 2. Mobile Apps Behvioural Analysis
**Code:**[Project-Mobile-App-Behavour-Analysis.ipynb](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh/blob/main/All%20Marketing%20Projects/Mobile%20App%20Behavior%20Analysis/Project-Mobile-App-Behavour-Analysis.ipynb)

**Description:** The dataset contains 50000 records with 12 features of mobile app data. Our dependent variable, 'Enrolled', is a key factor for this project. By exploring the features, I am able to assess the number of users who have signed up for the mobile app with regards to factors such as age, number of screens, minigame, and premium features. This project involves the following steps: loading data, cleaning and preprocessing, filling in missing values, exploratory data analysis (EDA), and feature engineering.

**Skills:** Data cleaning, Data preprocessing, Data insights, Data visualization, Feature Engineering, Model Building, Feature Scaling.

**Models:** Logistic Regression 

**Performance Measure:** Confusion Matrix, Accuracy, Precision, Recall and F1 score.

**Technology:** Python, Pandas, Numpy, Scipy, Seaborn, Matplotlib

**Result:** The analysis reveals that certain categories of users are more likely to sign up for the mobile app, such as younger age customers and those who play mini-games. It also provides information about customers who are likely to enroll in the last hours of the day, as well as during the last day of the week. Furthermore, customer sentiment is taken into account, and recommendations are made based on both positive and negative features of the app.

## 3. Customer Segmentation on App Usage
**Code:** [Project_Customer_Segmentation.ipynb](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh/blob/main/All%20Marketing%20Projects/Customer%20Segmentation%20Project/Project_Customer_Segmentation.ipynb)

**Description:** The dataset consists of 541909 observations with 8 characteristics of the sales data. The data identifies distinct groups of customers who have bought products or services. In this project, I used RFM to segment these groups, thereby facilitating the identification of loyal customers and those who are likely to cease using the services. Further details are provided in the accompanying Python file.

**Skills:** Data cleaning, Data preprocessing, Data insights, Data visualization.

**Technology:** Python, Pandas, Numpy, Scipy, Seaborn, Matplotlib, machine learning models like k-means clustering 

**Result:** We are performing an RFM analysis and plotting several graphs to gain insights into the data, in order to provide recommendations.

## 4. Churn Prediction Analysis on Telecommunication
**Code:**[Project_Churn_Prediction_Analysis.ipynb](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh/blob/main/All%20Marketing%20Projects/Churn%20Prediction%20Analysis/Project_Churn_Prediction_Analysis.ipynb)

**Description:** This dataset has 7,043 entries, each with 21 different characteristics. The Python file displays the list of attributes. This project involve's loading the data, cleaning and preparing it, fixing any missing values, doing exploratory data analysis, and examining the customer churn rate in relation to the various features.

**Skills:**  Data Wrangling, Exploratory Data Analysis, Statistical Analysis, Machine Learning, Data Visualization, Communication

**Technology:** Python, Pandas, Numpy, Scipy, Seaborn, Matplotlib.

**Result:** Final feature which the company has to target to reduce the churn and based on that the necessaru recommendation's have been given to the company.


# Projects based on Healthcare Analysis 

**Power Point Presentation:**[Project_Healtcare.pptx](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh/blob/main/Healthcare%20Analytics%20Final%20Projects/Healthcare%20Final%20Project%20PPT.pptx)

**Project Proposal:**[Project_Proposal.pptx](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh/blob/main/Healthcare%20Analytics%20Final%20Projects/Project%20Proposal%20-%20Healthcare%20Analytics.pdf)


**Description:** The project focuses on healthcare with the aim of analyzing waiting times for patients in Canada, with respect to various treatments and cases by province. We plan to compare pre-pandemic and post-pandemic data from 2008 to 2021 to identify any changes or improvements. Our goals include analyzing wait times (in days) at hospitals by province in relation to pre- and post-pandemic periods, as well as analyzing trends in the number of cases of specific treatments by the top provinces before and after COVID-19. Additionally, we aim to improve waiting times for cancer, cardiac, diagnostic imaging, and joint replacement treatments at hospitals by interpreting the data and presenting it visually to suggest solutions.

***More details about the dataset and project is given in the project presentation.***

**Skills:** Data Analysis, Data Visualization, Data Cleaning, Data Mining, Statistical Analysis, Project Management, Communication

**Technology:** Tableau

**Result:** 3 Tableau Dashboards and insights for hospitals across Canadian provinces to learn and improve their wait times post Covid.

1st Dashboard - Dataset Analysis

2nd Dashboard - Pre-Covid Wait Time Analysis

3rd Dashboard - Post-Covid Wait Time Analysis

You can view the entire tableau project from this link -

# PowerBI Project based on Hotel Booking Analysis

**Power BI:** [Project_Hotel_Booking](https://app.powerbi.com/home)

**Description:** Have you ever pondered the optimal time of year to book a hotel room, or the ideal duration of stay to secure the best daily rate? What if you could predict if a hotel would receive an unusually high number of special requests? This hotel booking dataset can help answer these questions!

This data set includes booking information for both a city hotel and a resort hotel, outlining when the booking was made, the length of stay, the number of adults, children and/or babies, and the number of available parking spaces, among other details. There is no personally identifiable information in the data. For further explanation, please visit this project].()

**Skills:** Requirements gathering, designing an analytical dashboard, analysing trends of the data

**Technology:** Power BI

# Microsoft Project

**Topic:** Food delivery application – Takeout express  and detail [go to project](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh/blob/main/Project%20Management%20Work/Final%20Project/Final%20Project%20Submission%20(1).mpp)

 **Microsoft project is needed to access the project.** 
 
# Certificates
These are all important certifications I have recived over the past few years, which prove my skill as a data analyst. [go to certficates]()
