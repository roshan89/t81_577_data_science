# T81 577 Applied Data Science for Practitioners

[Washington University in St. Louis](https://wustl.edu/)

Instructor: Asim Banskota

Spring 2020, Wednesday, 6:00 PM - 9:00 PM , Cupples II, Room L015

# Course Description

Organizations are rapidly transforming the way they ingest, integrate, store, serve data, and perform
analytics. In this course, students will learn the steps involved with designing and implementing data
science projects. Topics addressed include: ingesting and parsing data from various sources, dealing with
messy and missing data, transforming and engineering features, building and evaluating machine learning models, and
visualizing results. Using Python based tools such as Numpy, Pandas, and Scikit-learn, students will
complete a practical data science project that addresses the entire design and implementation process.
Students will also become familiar with the best practices and current trends in data science including
code documentation, version control, reproducible research, pipeline automation, and cloud computing. Upon completion of the course, students will emerge equipped with data science knowledge and skills that can be applied from day one on the job.

# Syllabus

Week|Content
----|----
Week 1 <br> **1/15/2020** |**Introductions** <ul><li>1.1. [Data science in practice](weekly_materials/week1/docs/data-science-in-practice.md) <li> 1.2. Introduction to Python Programming Language <ul> <li> 1.2.1. [Python introduction and set up](weekly_materials/week1/docs/python-introduction-and-set-up.md) <li> 1.2.2. [Jupyter Notebook and Lab](weekly_materials/week1/docs/jupyter-notebook-and-lab.md)  </ul> 1.3. [An introduction to Amazon Web Service (AWS)](weekly_materials/week1/docs/an-introduction-to-aws.md) </ul>**Assignment 1.1:** [Install anaconda and test Jupyter notebook](weekly_materials/week1/assignments/assignment-1.md) <br>**Assignment 1.2:** [AWS fundamentals](weekly_materials/week1/assignments/assignment-2.md) </ul>
Week 2 <br> **1/22/2020** |**Python Fundamentals** <ul><li> 2.1. [Basic data types](weekly_materials/week2/notebooks/basic-data-types.ipynb) <li> 2.2. [Data structure and iterables](weekly_materials/week2/notebooks/data-structure-and-iterables.ipynb)<li> 2.3 [Conditional, iteration, and function in Python](weekly_materials/week2/notebooks/conditional_iteration_function.ipynb)<li>2.4. [Map, filter, reduce, comprehension](weekly_materials/week2/notebooks/map-filter-reduce-comprehension.ipynb) </ul>**Assignment 2:** [Programming practice assignment](weekly_materials/week2/assignments/assignment2.ipynb)</ul>
Week 3 <br> **1/29/2020** |[**Coding Best Practices in Data Science** ](weekly_materials/week3/docs/coding-best-practices-in-data-science.md)<ul><li> 3.1. [Top-ten best-practices](weekly_materials/week3/docs/top-ten-best-practices.md) <li> 3.2. [Style guide for python code](weekly_materials/week3/docs/style-guide-for-python-code.md) <li>3.3. [Documenting python code](weekly_materials/week3/docs/documenting-python-code.md) <li>3.4. [Version control](weekly_materials/week3/docs/version-control.md) <li>  3.5. [Code linting](weekly_materials/week3/notebooks/linting.ipynb) </ul>**Assignment 3:** [Version control, project structure, and code documentation](weekly_materials/week3/assignments/assignment3.md) </ul>
Week 4 <br> **2/5/2020** |[**Modeling Overview**](weekly_materials/week4/docs/overview.md) <ul><li> 4.1. [Types of models](weekly_materials/week4/docs/types-of-models.md) <ul><li> 4.1.1. [Causal/Prescriptive/Predictive](weekly_materials/week4/docs/types-by-purpose.md) <li> 4.1.2. [Statistical vs Machine learning](weekly_materials/week4/docs/types-by-framework.md) <li> 4.1.3. [Blackbox vs Explainable](weekly_materials/week4/docs/types-by-interpretability.md) </ul> 4.2. [Model development steps](weekly_materials/week4/docs/model-development-steps.md) </ul>
Week 5 <br> **2/12/2020**| [**Accessing Data**](weekly_materials/week5/docs/retrieving-data.md) <ul><li> 5.1. [Introduction to RESTful APIs](weekly_materials/week5/docs/intro-to-web-api.md) <li> 5.2. [Interacting with API using Postman](weekly_materials/week5/docs/postman.md) <li> 5.3. [Getting data from API](weekly_materials/week5/notebooks/accessing-data-with-requests.ipynb) <li> 5.4. [Parsing JSON data](weekly_materials/week5/notebooks/parsing-json.ipynb) <li> 5.5. [Reading text files](weekly_materials/week5/docs/read-text-files.md) <li> 5.6. [Fetching data from PostgreSQL database](weekly_materials/week5/docs/accessing-data-from-postgres.md) </ul> **Assignment:** Finalization of final project topic and data set (Not graded)</ul>
Week 6 <br> **2/19/2020**| **Numpy/Pandas for Data Wrangling** <ul><li> 6.1. [Numpy data structure](weekly_materials/week6/notebooks/numpy-data-structure.ipynb) <li> 6.2. [Numpy functions](weekly_materials/week6/notebooks/numpy-functions.ipynb) <li> 6.3. [Vectorization](weekly_materials/week6/notebooks/vectorization.ipynb) <li> 6.4. [Pandas basics](weekly_materials/week6/notebooks/pandas-basics.ipynb) <li> 6.5.[Data manipulation with Pandas](weekly_materials/week6/notebooks/data-manipulation-with-pandas.ipynb) <li> 6.6. [Vizualization in Pandas](pandas-vizualization.ipynb) </ul> **Assignment 4:** [Exercise with Numpy and Pandas](weekly_materials/week6/assignment/assignment4.ipynb) </ul>
Week 7 <br> **2/26/2020**| **Exploratory Data Analysis (EDA)** <ul><li> 7.1. [Introduction to EDA](weekly_materials/week7/docs/eda.md) <li> 7.2. [Univariate analysis](weekly_materials/week7/notebooks/eda-univariate.ipynb) <li> 7.3. [Bivariate analysis](weekly_materials/week7/notebooks/eda-bivariate.ipynb) <li> 7.4. [Temporal analysis](weekly_materials/week7/notebooks/temporal-eda.ipynb) <li> 7.5. [Spatial analysis](https://nbviewer.jupyter.org/github/abanskota/t81_577_data_science/blob/master/weekly_materials/week7/notebooks/geo-visualization-folium.ipynb) </ul> **Assignment 5:** [Vizualization and data summary](weekly_materials/week7/assignment/assignment5.md) </ul>
Week 8 <br> **3/4/2020**| [**Data Preprocessing**](weekly_materials/week8/docs/preprocessing.md) <ul><li> 8.1.[Scikit-learn preprocessing](weekly_materials/week8/docs/intro-to-scikit-learn.md)<li>8.2. [Missing value treatments](weekly_materials/week8/docs/missing-value.md) <li> 8.3. [Standardization and Binning](weekly_materials/week8/docs/std-bin.md) <li> 8.4. [Categorical encodings](weekly_materials/week8/notebooks/categorical-encoding.ipynb) <li> 8.5. [Resampling](weekly_materials/week8/notebooks/resample.ipynb) <li> 8.6. [Feature engineering](weekly_materials/week8/docs/feature-engineering.md) </ul>**Assignment 6:** [Data preprocessing](weekly_materials/week8/assignment/assignment6.md) </ul>
Week 9 <br> **3/25/2020** |**Algorithms for predictive modelling- Part I** <ul><li>9.1. [Basic-modelling-terminologies](weekly_materials/week9/docs/key-terminologies.md)<li> 9.2. [linear regression](weekly_materials/week9/notebooks/linear-regression.ipynb)<li> 9.3. [Naive Bayes classification](weekly_materials/week9/notebooks/naive-bayes-classifier.ipynb) <li> 9.4. [Logistic regression](weekly_materials/week9/notebooks/logistic-regression.ipynb) <li> 9.5. [Tree based algorithms](weekly_materials/week9/notebooks/tree-based-algorithms.ipynb)<li>9.6. [K-means clustering](weekly_materials/week9/notebooks/k-means-clustering.ipynb) </ul> 
Week 10 <br> **4/1/2020** |**Algorithms for predictive modelling- Part II** <ul><li>10.1. [Support vector machine](weekly_materials/week10/notebooks/support-vector-machine.ipynb)<li> 10.2. [Neural Network](weekly_materials/week10/notebooks/neural-network.ipynb)<li>10.3. [Streamlining workflows with pipeline](weekly_materials/week10/notebooks/scikit-learn-pipeline.ipynb)<li>10.4. [Model Evaluation](weekly_materials/week10/docs/model-evaluation.md)</ul>**Assignment 7:** [Model Fitting and evaluation](weekly_materials/week10/assignment/assignment7.md) </ul>
Week 11 <br> **4/8/2020** | **Best practices in Machine Learning** <ul><li> 11.1. [Reducing bias and variances](weekly_materials/week11/docs/bias-variance-reduction.md) <li> 11.2. [Selecting train/dev/test dataset](weekly_materials/week11/docs/training-testing.md) <li> 11.3. [Hyperparameter tuning](weekly_materials/week11/notebooks/Hyperparameter+Tuning.ipynb) </ul> **Assignment:** [hyperparameter tuning](weekly_materials/week11/assignment/assignment8.md) </ul>
Week 12 <br> **4/22/2020** | **Deploy a Machine Learning model** <ul><li> 13.1. [Overview of model deployment](weekly_materials/week12/docs/model-deployment.md) <li> 13.2 [Basic terminologies](weekly_materials/week12/docs/terminologies.md) <li> 13.3. [Deploy a model as a Flask app](weekly_materials/week12/docs/model-as-a-service.md) <li> 13.4. [Docker for data science](weekly_materials/week12/docs/docker-for-ds-.md) <li>13.5. [Introduction to Airflow]() </ul> **Assignment:** Final project due on April 30 </ul>
