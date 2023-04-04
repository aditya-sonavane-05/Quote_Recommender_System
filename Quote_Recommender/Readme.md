# Inspirational Quotes Dataset and Recommender System

This repository contains a script to scrape a website and extract inspirational quotes and their respective authors, as well as a dataset generated from the extracted quotes. Additionally, the repository includes a model that ranks the top-5 quotes based on user preferences and mouse clicks, and a recommender system that suggests quotes to users based on their past interactions.

## Requirements
* ### Python 3

* ### Beautiful Soup 4

*  ### Pandas

* ### Scikit-Learn

* ###  Streamlit

* ### Regex

* ### NLTK


## Usage
Clone the repository using git clone.
Install the required dependencies using pip install -r requirements.txt.
Run the application using streamlit run app.py.


## Steps for Web Scraping
Web scraping is the process of extracting data from websites. Here are the general steps involved:

* Identify the website and data to be scraped.

* Analyze the website's structure and determine the appropriate method for scraping the data.

* Write code to automate the scraping process, which typically involves sending requests to the website's server, parsing the HTML code to extract the desired data, and storing the data in a suitable format.

* Test the code to ensure it works as expected and can handle various scenarios.

* Optimize the scraping process to improve efficiency and minimize impact on the website's server.

* Monitor the scraping process and adjust as needed to ensure it continues to work properly and does not violate any legal or ethical guidelines.

Web scraping can be a powerful tool for gathering data from websites, but it is important to be aware of potential legal and ethical implications and to use it responsibly.





## Steps for Building a Recommender System in Machine Learning

This project involves building a recommender system using machine learning techniques to recommend inspirational quotes to users. The system uses natural language processing (NLP) to preprocess and extract features from the quotes, and a collaborative filtering algorithm to make personalized recommendations.


* #### Data Collection - Gather data on user preferences, item attributes, and any other relevant information. In this case, we scraped a website to gather inspirational quotes and their authors.

* #### Data Preprocessing - Clean, transform, and prepare the data for modeling. This involved using regular expressions to remove any unwanted characters or formatting, as well as NLP techniques such as tokenization, stop word removal, and stemming to prepare the quotes for analysis.

* #### Feature Extraction - Use NLP techniques such as TF-IDF to extract features from the preprocessed text data that can be used to measure similarity between quotes.

* #### Model Selection - Choose the appropriate algorithm for the type of data and problem at hand. In this case, we chose to use a collaborative filtering algorithm to make personalized recommendations.

* #### Model Training - Train the model on a subset of the data, using a training and validation set to optimize performance.

* #### Model Evaluation - Test the model on a separate test set to evaluate its performance and fine-tune any parameters.

* #### Deployment - Integrate the model into a production environment and continuously monitor and update it as needed. We used the Streamlit library to create a simple and user-friendly interface for our recommender system.

## Model Details
The model uses the Surprise library to build a collaborative filtering recommender system. The system recommends quotes based on the similarity of the quotes in the dataset to the quotes that the user has previously rated. We used cosine similarity as the similarity measure for the collaborative filtering algorithm.

## Conclusion
This project demonstrates how machine learning techniques, specifically NLP and collaborative filtering, can be used to build a personalized recommender system. By using natural language processing techniques to preprocess and extract features from the quotes, the system is able to make more accurate and relevant recommendations. By using collaborative filtering, the system is able to make personalized recommendations based on the user's previous ratings. The Streamlit interface provides an easy and intuitive way for users to interact with the recommender system and receive personalized recommendations.
