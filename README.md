# Suggest Mercari price using deep learning. 
***
## Background
This project is initiated from Kaggle’s ongoing competition, named [“Mercari Price Suggestion Challenge”](https://www.kaggle.com/c/mercari-price-suggestion-challenge) (Kaggle, 2018). 

Mercari is Japan’s biggest community-powered shopping application, which is organizing a marketplace where sellers are putting their products to sell. 

One major service provided by Mercari is to offer price suggestions to the sellers.
***
## Objective
This project seeks to solve the problem of building an algorithm for an electronic commerce company to suggest the right product prices based on the information provided by the sellers. 
***
## Data Exploration
* Distribution of the price after log-transformed

![Alt text](https://github.com/leizhipeng/DL_Mercari_Price_Suggestion/blob/main/Figures/price.png?raw=true "Optional Title")

* Distribution of the price after log-transformed

![Alt text](https://github.com/leizhipeng/DL_Mercari_Price_Suggestion/blob/main/Figures/word_cloud.png?raw=true "Optional Title")
  
***
## Algorithms
### Benchmark: Linear Regression
* Term-document matrix
* Lasso linear regression 

### Approach 1: LDA and Deep Neural Network.
![Alt text](https://github.com/leizhipeng/DL_Mercari_Price_Suggestion/blob/main/Figures/approach1.png?raw=true "Optional Title")

### Approach 2: Word Embedding and Deep Neural Network. 
![Alt text](https://github.com/leizhipeng/DL_Mercari_Price_Suggestion/blob/main/Figures/approach2.png?raw=true "Optional Title")

***
## Conclusion
From the RMSLE error, Approach 1 is slightly better than Approach 2. However, the LDA technique in Approach is time-consuming, as it is not supported by GPU acceleration. 