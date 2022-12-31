# **Restaurant Recommendation Based on Location**

---

## **Project Overview:**

This project aims to develop a recommendation system that suggests restaurants to users based on their current location. The system will use data from the Yelp dataset on Kaggle, which contains information on businesses in the restaurant industry such as location, ratings, and categories.

---

## **About the Dataset:**

The Yelp dataset on Kaggle contains information on businesses in the restaurant industry, including their location, ratings, and categories. The dataset is extensive, containing information on over 180,000 businesses. It is an ideal dataset for this project as it contains relevant and up-to-date information on restaurants, making it suitable for building a recommendation system.

---

## **Exploratory Data Analysis (EDA):**

Before implementing the recommendation system, we will conduct EDA on the dataset to understand the distribution of the data and identify any patterns or trends. This will help us to better understand the data and ensure that the recommendation system is based on accurate and relevant information.

---

## **Clustering:**

To implement the recommendation system, we will use the K-Means algorithm to cluster the data based on the location of the restaurants. The K-Means algorithm is a popular machine learning algorithm that is suitable for clustering data based on distance. It works by dividing the data into a specified number of clusters and iteratively reassigning data points to the cluster with the closest mean.

---

## **Recommendation System:**

Once the data has been clustered, we can use the clusters to suggest the top 5 restaurants from the cluster closest to the user's location. The recommendation system will simply return the top 5 restaurants based on ratings and proximity to the user's location.

---

## **Tools and Technologies:**

- Python
- K-Means algorithm
- Pandas
- Numpy
- GeoPandas
- Folium
- Plotly
- Seaborn

---

## **Expected Outcome:**

The project will result in a recommendation system that suggests restaurants to users based on their current location. The system will use the K-Means algorithm to cluster the data and recommend the top 5 restaurants from the cluster closest to the user's location.