
# SNAP Recommendation Engine

## About :
A Graph Based Recommendation Engine which recommends appropriate similar products, co-purchased products and high confidence products similar to one viewed by user using the Amazon SNAP Co-Purchasing Dataset.

## Original Dataset Information

### amazon-meta.txt.gz -
Amazon product metadata and reviews from summer 2006
The data was collected by crawling Amazon website and contains product metadata and review information about 548,552 different products (Books, music CDs, DVDs and VHS video tapes).

For each product the following information is available:

- Title
- Salesrank
- List of similar products (that get co-purchased with the current product)
- Detailed product categorization
- Product reviews: time, customer, rating, number of votes, number of people that found the review helpful
- The data was collected in summer 2006.

### amazon0601.txt.gz -
Amazon product co-purchaisng network from June 01 2003

Network was collected by crawling Amazon website. It is based on Customers Who Bought This Item Also Bought feature of the Amazon website. If a product i is frequently co-purchased with product j, the graph contains a directed edge from i to j.

The data was collected in June 01 2003.

![image](https://user-images.githubusercontent.com/72119231/175798861-b65234b1-06bc-4b5b-a5f3-3c6a5c6464ac.png)

Source: 
 - https://snap.stanford.edu/data/amazon-meta.html
 - https://snap.stanford.edu/data/amazon0601.html
 
## Features of Recommendation Engine -

- Product Recommendation System basis of Feature Extracted from the product details and the co-purchases made.

- Similar Products Recommendation System which might make customers explore other options

- Recommendation of products based on their Consumer Confidence and category similarity using different metrics.


## Solution Details-

Considering the fact customer is searching for a product or viewing a product . We try to recommend products to the consumer based on various aspects of product features, customer ratings and co-purchases made among varies products listed.

![image](https://user-images.githubusercontent.com/72119231/175799027-dafcd190-bb40-4254-bd51-bda1d7fca420.png)


### Solution_P1.ipynb - 
Data Exploration, Exploratory Data Analysis and Recommendation System basis of Feature Extracted from the product details and the co-purchases made.

### Solution_P2.ipynb - 
Feature Extraction and Similar Products Recommendation System which might make customers explore other options

### Solution_P3.ipynb - 
Customer Reviews Feature Extraction,Clustering of products into various group based on Customer Confidence and Recommendation of products based on their consumer confidence and category similarity using different metrics.

### trial.py - streamlit demo

### Solution_Inference.ipynb - 
A inference notebook to showcase all three solutions together.

