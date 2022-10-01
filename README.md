# What is in your basket? — Instacart Dataset Exploration

![project_header](https://github.com/adzict/instacart_data_exploration/blob/main/img/instacart_logo.jpg)

## Table of Contents

1. [ Project Introduction ](#Project_Introduction)
2. [ Technologies Used ](#Technologies_Used)    
3. [ Methods Used ](#Methods_Used)
4. [ Project Description ](#Project_Description)
   * [ 1. Data Sources ](#Data_Sources)
   * [ 2. File Descriptions ](#File_Descriptions) 
5. [ Feature Notebooks and Deliverables ](#Notebooks_deliverables)
6. [ Most Important Findings ](#Findings)
   * [1. Which categories of businesses are getting top reviews?](#business_cat)
   * [2. How often do businesses get reviewed over time?](#frequency_reviews)
   * [3. Which business categories get bad reviews?](#bad_reviews)
   * [4. Accuracy results of Sentiment Analysis using VADER](#vader)
   * [5. Predicting the sentiment using different classifiers](#modeling)
   * [6. Conclusion and Future Recommendations](#conclusion)
7. [ Acknowledgments ](#Acknowledgments)
8. [ Licences ](#Licences)
9. [ Contact ](#Contact)

## Project Introduction
<a name="Project_Introduction"></a>

The aim of the project is to explore and analyze the Instacart Dataset, and make actionable recommendations and conlcusions regarding customer habits, and needs.

## Technologies Used
<a name="Technologies_Used"></a>
* [Python](https://www.python.org/)
* [Numpy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)

## Methods Used
<a name="Methods_Used"></a>
* Data Processing / Data Cleaning
* Data Analysis
* Descriptive Statistics
* Data Visualization
* Reporting

## Project Description
<a name="Project_Description"></a>

Instacart is a popular app used for grocery ordering and delivery. They make it quite easy for you to fill your refrigerator and pantry with favorite produce, anytime you need them. In 2017, they published a Kaggle competition which challenged the Data Science community to create a powerful recommendation system for their customers. They published an anonymized dataset that contained a sample of over 3 million grocery orders from more than 200,000 Instacart users.

I was curious enough to explore and analyse the dataset. However, I will leave out the recommender system part for another time, and focus on exploratory data analysis (EDA), and answering general questions about customer habits, most popular produce and departments and similar.

In order to perform an analysis, I started by asking general questions about customer habits, popular produce, dominant departments, returning customers and other questions that seemed relevant. I ended up with a list of questions I deemed interesting enough to answer:

* When do people place their orders?
* How many orders are there per customer?
* How often do customers reorder?
* Which products are frequently ordered?
* Which products are usually reordered?
* What is the proportion between reordered and newly ordered items?
* How many products are there in the cart usually?
* What are the most popular aisles per products ordered?
* What are the most popular departments?

### Data Sources
<a name="Data_Sources"></a>

The data used for this analysis is available on the [Instacart Kaggle Webpage](https://www.kaggle.com/competitions/instacart-market-basket-analysis/data). It contains 6 files: orders, products, departments, aisles, order products prior, and order products train.

### File Descriptions
<a name="File_Descriptions"></a>

* [Data](https://github.com/adzict/instacart_data_exploration/tree/main/data) - folder containing competition data
* [Images](https://github.com/adzict/instacart_data_exploration/tree/main/img) - images 
* [Instacart Dataset Exploration](https://github.com/adzict/instacart_data_exploration/blob/main/Instacart%20Dataset%20Exploration.ipynb) - Notebook containing the complete process of Data Exploration and Analysis

## Feature Notebooks and Deliverables
<a name="Notebooks_deliverables"></a>
### Blog Posts

* Blog post on Instacart Dataset Exploration: [What is in your basket? — Instacart Dataset Exploration](https://adzic-tanja.medium.com/what-is-in-your-basket-instacart-dataset-exploration-11eb9f123680)

### Structure of Notebooks
<details>
   <summary>Collapse</summary>

      1. Data Preprocessing and Basic EDA

            1. Imports
            2. Data
               2.1 Orders Dataset
               2.2 Products Dataset
               2.3 Aisles Dataset
               2.4 Departments Dataset
               2.5 Order Products Dataset
               2.6 Merging Dataframes
            3. Business Case
               3.1 What is the structure of our data?
               3.2 When do people place their orders?
               3.3 How many orders are there per customer?
               3.4 How often do customers reorder?
               3.5 Which products are frequently ordered?
               3.6 Which products are usually reordered?
               3.7 What is the proportion between reordered and newly ordered items?
               3.8 How many products are there in the cart usually?
               3.9 What are the most popular aisles per products ordered?
               3.10 What is the share of orders per aisle?
               3.11 What are the most popular departments?
               3.12 What is the share of orders per department?
            
</details>  

### Presentation
Link to the presentation: [Instacart Dataset Exploration Presentation]()