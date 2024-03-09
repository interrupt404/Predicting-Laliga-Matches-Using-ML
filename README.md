# Laliga Football Match Prediction

## Project Overview

In this project, we aim to predict the outcomes of football matches in Laliga, one of the top professional football leagues in Spain. We will utilize machine learning techniques to forecast the winners of matches based on historical data.

### Project Steps

1. **Data Scraping:** We will gather match data from FBref using web scraping techniques with the BeautifulSoup library in Python. The scraped data will include various match statistics such as goals scored, possession percentages, shots on target, etc.

2. **Data Cleaning:** Once we have collected the raw data, we will preprocess and clean it to ensure consistency and remove any irrelevant or erroneous information. This step involves handling missing values, converting data types, and performing any necessary feature engineering.

3. **Machine Learning Model:** With the cleaned data, we will build a machine learning model using scikit-learn. The model will be trained on historical match data to learn patterns and relationships between different variables and the match outcomes.

4. **Prediction:** After training the model, we will use it to make predictions on upcoming Laliga matches. The model will take match characteristics as input and output the predicted winner of each match.

5. **Evaluation and Improvement:** Finally, we will evaluate the performance of our predictions using appropriate metrics and iterate on our model to improve its accuracy and reliability.

## Local Setup

### Installation

To replicate this project locally, follow these steps:

1. Install JupyterLab.
2. Ensure you have Python 3.8 or later installed.
3. Install the required Python packages:
   - pandas
   - requests
   - BeautifulSoup
   - scikit-learn

### Data

The match data will be scraped from [FBref](https://fbref.com/en/) using the scraping script provided in the project repository.

## Code

You can access the complete code for this project in the provided GitHub repository. The project is divided into two main parts:

1. **Web Scraping Laliga (`Web Scraping Laliga.ipynb`):** This Jupyter notebook contains the code for scraping match data from FBref using BeautifulSoup and saving it to a CSV file (`matches.csv`).

2. **Predicting Match Scores (`Predicting_Match_Scores.ipynb`):** In this notebook, we build and train our machine learning model using scikit-learn. We also make predictions on Laliga matches using the trained model.

Feel free to explore the code and adapt it to your specific requirements. Happy predicting!
