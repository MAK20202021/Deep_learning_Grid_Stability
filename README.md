# Deep_learning_Grid_Stability
This project is based on the "Electrical Grid Stability Simulated Dataset", created by Vadim Arzamasov (Karlsruher Institut für Technologie, Karlsruhe, Germany) and donated to the University of California (UCI) Machine Learning Repository ([link](https://archive.ics.uci.edu/ml/datasets/Electrical+Grid+Stability+Simulated+Data+)), where it is currently hosted. 
After Learning from the project ([link](https://www.kaggle.com/code/pcbreviglieri/predicting-smart-grid-stability-with-deep-learning)), I explored the utilization of GridSearchCV to perform the hyperparameter tuning with the same dataset to do more analysis in deep learning.
The Main objective of the analysis is to focus on a specific type of Deep Learning and the benefits that this analysis brings to the business or stakeholders of this data is to predict the stability of grid more accurately.

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
This exercise provides a better understanding of deep learning approach in case of predicting grid stability. I used GridSearchCV library to get the best parameters for the model such as layers and nodes and activation function. I got 97.05% accuracy of the model. From hyperparameter tuning I got four layers with ReLu activation. For further analysis with this dataset, we can increase the number of epochs and it will increase the prediction accuracy.

## Reference
