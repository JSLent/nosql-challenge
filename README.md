## UK Food Standards Analysis: Eat Safe, Love
# nosql-challenge
Repo for Module 12 Challenge

## Description

This project involves analysis of various establishments across the United Kingdom, evaluated by the UK Food Standards Agency and given a food hygiene rating. The analysis is performed using a series of Jupyter notebooks that interact with a MongoDB database. The notebooks demonstrate how to connect to a MongoDB database, run queries, and display the results in a Pandas DataFrame.

## Installation

1. Clone the repository: git clone https://github.com/yourusername/your-repo-url.git
2. Install the required dependencies: pip install -r requirements.txt
3. Import the data provided in the establishments.json file from your Terminal.
4. Use the following command to import the data: mongoimport --db uk_food --collection establishments --file ./path_to_your_file/establishments.json

## Usage

1. Open the desired notebook in Jupyter.
3. Run the cells in the notebook to interact with the database and perform the analysis.
2. Database and Jupyter Notebook Set Up: The project includes a notebook (NoSQL_setup_starter.ipynb) that guides you through setting up your MongoDB database and preparing it for use.
3. Database Update: The project includes steps to update the database with new information, such as adding a new restaurant and updating existing records.
4. Exploratory Analysis: The project includes a notebook (NoSQL_analysis_starter.ipynb) that guides you through an exploratory analysis of the data, answering specific questions about the establishments.


