# Deep_learning_Grid_Stability
This project is based on the "Electrical Grid Stability Simulated Dataset", created by Vadim Arzamasov (Karlsruher Institut für Technologie, Karlsruhe, Germany) and donated 
to the University of California (UCI) Machine Learning Repository ([link](https://archive.ics.uci.edu/ml/datasets/Electrical+Grid+Stability+Simulated+Data+)), where it is currently hosted. 
After Learning from the project (link), I explored the utilization of GridSearchCV to perform the hyperparameter tuning with the same dataset to do more analysis in deep learning.

Unsupervised Machine Learning is used when Data is not labeled that means data points have unknown outcome. Two types of unsupervised machine learning is available - Clustering and Dimensionality Reduction. In case of clustering, KMeans, Hierarchical Agglomerative clustering, DBSCAN, Mean Shift are common algorithms and in case of dimensionality reduction, PCA, Non-negative Matrix Factorization are very common algorithms.
The main objective of the analysis is to predict the customer channel whether they are from hotel/restaurant/café or from retail business depending on their purchase history of different items. Here we focused on the clustering algorithm to build the model. The benefits of this analysis are to provide a better idea about the customers to enhance the facilities to the wholesale distributors. We chose three different clustering models such as KMeans, Agglomerative and Mean Shift and chose the right model from comparing their ROC_AUC scores.

## Acknowledgement
This project is for [IBM Machine Learning Professional Certificate Program](https://www.coursera.org/professional-certificates/ibm-machine-learning?).
Thanks to Coursera and IBM for arranging this project to strengthen our knowledge. 
## Installation
This project needs Anaconda package(Anaconda3), Jupyter Notebook (6.1.4).

## File Description
The source codes are as follows:
- Final_Project_Unsupervised.ipynb
- Final_Project_Unsupervised.html
- Report_Unsupervised_Learning.pdf

## Discussion
After completing this project, I understand how we can build the unsupervised machine learning models and evaluate them.
