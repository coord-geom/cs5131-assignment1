# cs5131-assignment1
## An analysis of Singapore HDB Resale Prices via Machine Learning
## Done by Daniel Chan, Edden Chew, and Zhi Yuan

In this assignment, we used Regression Algorithms to predict the Resale Price of HDB flats. A summary of `main.ipynb` is as follows:
- Data Cleaning and Exploration
    - Collated the Data across the 5 csv files
    - Manually calculated `remaining_lease` for all data
    - Did price adjustment in accordance to inflation
    - Pulled the Latitude and Longitude for all flats via onemap API
    - Data Exploration to find variables which affect the resale price to a large degree
- Regression
    - Simple Linear Regression
    - Ridge Regression
    - Elastic Net Regression
    - An attempt via K-means Clustering via Latitude and Longitude, then Linear Regression from there. 
- Analysis
    - Comparison of ML Models
    - Proof of Concept via Visualisation Libaries
    - Justifying the flaws of our created models
- Learning Points
