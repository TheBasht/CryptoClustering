# Cryptocurrency Clustering Project

## About the Project
This project is about grouping cryptocurrencies into clusters using machine learning. We look at how their prices change and find patterns to put similar ones together.

---

## What We Did
1. **Loaded the Data**  
   We got the cryptocurrency data from a file.

2. **Prepared the Data**  
   We scaled the data to make everything equal.

3. **Found the Best Number of Groups (k)**  
   We used the Elbow Method to find the best number of clusters for the data.

4. **Clustered the Cryptos**  
   We grouped the cryptocurrencies using K-Means and added the cluster labels to the data.

5. **Optimized with PCA**  
   We used PCA to make the data smaller and easier to work with.

6. **Compared Results**  
   We compared the clusters from the original data and the PCA data.

---

## Tools We Used
- **Python Libraries:**  
  - `pandas` for handling data  
  - `hvplot` for making graphs  
  - `scikit-learn` for machine learning  

---

## What We Learned
- The best number of groups (`k`) is **4**.  
- Using PCA makes the clusters easier to see and work with.  

---

## Conclusion
We grouped cryptocurrencies into clusters to understand them better. Machine learning helps us find patterns and make sense of the data.
