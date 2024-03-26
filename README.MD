# Coursera: IBM Data Science Professional Certificate
## Course 10: Capstone

### Purpose:

- This is the final course/activity/project of IBM's Data Science Certificate via Coursera. In this capstone, an entire Data Science project is completed from data gathering, cleaning, wrangling, EDA with both SQL and Pandas, visualizations, dashboard, and predictive models. The goal is to predict if SpaceX's Falcon 9 first stage will land successfully in order to possibly be used for reuse as rocket engine reuse is critical in the cost of launches. 

**Below is from the assignment itself**
___

SpaceX advertises Falcon 9 rocket launches on its website, with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch

## Overall Objectives

- Utilize data science methodologies to define and formulate a real-world business problem
- Convert a JSON file and use web scraping to create a Python Pandas dataframe and use throughout
- Develop/use Python code throughout to view/manipulate data in Pandas dataframes
- Create several Jupyter notebooks 
- Create a dashboard
- Create predictive models

### Collecting Data

    API
        Request to the SpaceX API
        Clean the requested data
    Web Scraping
        Web scrap Falcon 9 launch records with BeautifulSoup:
        Extract a Falcon 9 launch records HTML table from Wikipedia
        Parse the table and convert it into a Pandas dataframe

### Data Wrangling

    Perform exploratory Data Analysis and determine Training Labels 
        Exploratory Data Analysis
        Determine Training Labels

### EDA Using SQL

    Understand the Spacex DataSet
    Load the dataset into the corresponding table in a Db2 database
    Execute SQL queries to answer assignment questions

### EDA Using Pandas and Matplotlib

    Perform exploratory Data Analysis and Feature Engineering using Pandas and Matplotlib
        Exploratory Data Analysis
        Preparing Data Feature Engineering

### Launch Sites Locations Analysis with Folium

    Mark all launch sites on a map
    Mark the success/failed launches for each site on the map
    Calculate the distances between a launch site to its proximities

### Dashboard with Plotly Dash

    Analyze launch records interactively

### Machine Learning Prediction
    Determine Training Labels
    Standardize the data
    Split into training data and test data
    Find best Hyperparameter for Logistic Regression, SVM, Decision Trees, and K Nearest Neighbors 
    Find the method that performs the best

