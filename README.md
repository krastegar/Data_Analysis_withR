# Multivariate Statistics with some ML
## Introduction
This page is meant to demonstrate my understanding of R programming language as well as showcase interesting statistical techniques used to analyze multivariate data sets. I have two projects showcased on this page and both of these projects use the same dataset found in this paper Hinestrosa, J.P., Kurzrock, R., Lewis, J.M. et al. Early-stage multi-cancer detection using an extracellular vesicle protein-based blood test. Commun Med 2, 29 (2022). https://doi.org/10.1038/s43856-022-00088-6. Here I am intending to demonstrate how the power of data analysis and statistics can play a huge roll in diagnosis of cancer. 

#### GitHub Page link for both Projects:
https://krastegar.github.io/Data_Analysis_withR/

### Project 1: Recursive Feature Elimination (RFE) with Dimesonal Reduction Techniques on Cancer Cohort
Since the dataset is large, I used an unsupervised machine learning clustering algorithm called k-mediods to visualize the optimal amount of clusters within the cohort. After clustering, I performed a PCA analysis to determine what the clusters are made out of and see how much variation does each variable have towards different types of cancers. To improve clustering I implemented the RandomForest machine learning algorithm to determine which variables are the most important for classify different types of cancers. Once the most important features were picked, PCA and NMDS analysis were run to deteriment if we can see better separation between cancer types and to visualize which 

### Project 2: Logistic Regression of Cancer Status (Healthy vs Cancer)
In this notebook I am analyzing a patient cohort that are split up into two different groups (Cancer or Healthy) and using a logistic regression model to determine if specific protein concentration would be good indicators for determining if a patient is healthy or has cancer. I determine the best binomial glm by comparing different models using likelihood ratio's, as well as, using AIC scores. 
