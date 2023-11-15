# EX 10: Simulating Clustering using WEKA Data mining and Analysis Tool

## Date: 13/10/2023

## AIM:
To perform a classification technique using WEKA tool

## WEKA:
<div align="justify">
Weka is a comprehensive software that lets you to preprocess the big data, apply different machine learning algorithms on big data and compare various outputs. This software makes it easy to work with big data and train a machine using machine learning algorithms. This tutorial will guide you in the use of WEKA for achieving all the above requirements.
WEKA - an open source software provides tools for data preprocessing, implementation of several Data mining and Machine Learning algorithms, and visualization tools so that you can develop machine learning techniques and apply them to real-world data mining problems. What WEKA offers is summarized in the following diagram −

![image](https://github.com/SAILESHKUMAR33/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/113497410/c50384bd-4839-442e-be9d-e78fef688687)


## CLUSTERING:
<div align="justify">
Clustering or cluster analysis is a machine learning technique, which groups the unlabelled dataset. It can be defined as "A way of grouping the data points into different clusters, consisting of similar data points. The objects with the possible similarities remain in a group that has less or no similarities with another group." It does it by finding some similar patterns in the unlabelled dataset such as shape, size, color, behavior, etc., and divides them as per the presence and absence of those similar patterns. It is an unsupervised learning method, hence no supervision is provided to the algorithm, and it deals with the unlabeled dataset.

## PROCEDURE:
1. In the WEKA explorer select the Preprocess tab. Click on the Open file ... option and select the iris.arff file in the file selection dialog. <br>
![image](https://github.com/SAILESHKUMAR33/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/113497410/22a5ee85-75bd-4dd5-8a56-ed3d973241af)
2. Click on the Cluster TAB to apply the clustering algorithms to our loaded data. Click on the Choose button. Now, select EM as the clustering algorithm. <br>
![image](https://github.com/SAILESHKUMAR33/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/113497410/6dea7d0e-5cfb-492d-9593-4fbda0895d5c)
3. In the Cluster mode sub window, select the Classes to clusters evaluation option <br>
![image](https://github.com/SAILESHKUMAR33/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/113497410/2ca8620b-4c10-4219-840f-7b012fc2f67c)
4. Click on the Start button to process the data. After a while, the results will be presented on the screen. <br>
![image](https://github.com/SAILESHKUMAR33/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/113497410/94f59111-d726-4727-b9a5-385686c04430)
5. From the output screen, you can observe that − There are 5 clustered instances detected in the database. The **Cluster 0 represents setosa**, **Cluster 1 represents virginica**, **Cluster 2 represents versicolor**, while the last two clusters do not have any class associated with them. <br>
![image](https://github.com/SAILESHKUMAR33/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/113497410/6016ecdb-9a52-44c8-979c-425bf6f008e0)
6. To visualize the clusters, right click on the EM result in the Result list. <br>
![image](https://github.com/SAILESHKUMAR33/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/113497410/aca4d7de-b5eb-4216-a311-e0052b7add89)
7. Select Visualize cluster assignments.<br>
![image](https://github.com/SAILESHKUMAR33/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/113497410/a638236e-d579-4038-8872-481d63d10615)

## RESULT:
Thus the simulation of clustering technique has been executed using WEKA tool successfully.
