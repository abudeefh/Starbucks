DSND Capstone Challenge

Motivation:
The Starbuck app is a great addition to Starbucks where it shows that the company cares about its costumers and most importantly, cares about keeping up with the technology. The data I have analysed is a simplified version that does mimic the mobile app data. The main goal in this project is to collect and analyse transaction, demographic and offer data to determine which demographic groups respond best to which offer type.

Packages Used:
The following packages are required to execute the code in the jupyter notebook.
-numpy
-pandas
-sklearn
-matplotlib
-seaborn

Questions to Answer:
1.	In terms of the customers’ gender, who is dominant?
2.	If we look at it from a timeline point of view, how are customers increasing per gender
3.	In terms of age, who is dominant?
4.	In terms of income, what is the dominant income range for our customers
5.	What percentages of transactions are completed?
6.	Is there a link between the offer type and the response of the costumer?  In other words, what offers do get the highest completion rates/view rates?
7.	Can we build a model that can predict the behaviour of our costumers
8.	Who should receive offers on their app and what kind of offers?

Implementation:
What I did for the data is the following:
1. View the data and graph it to make sense out of it.
2. Built a machine learning model that predicts how much someone will spend based on demographics and offer type using unsupervised machine learning. 
Understand the importance of each variable in the model

Apply principal component analysis (PCA) from  sklearn  to find the vectors of maximal variability

Take the transformed data and apply clustering techniques to identify groups using  k-means method 

3. Check which clusters have the highest spending and what are their characteristics

refinement:
To make sure I get the best results and I chose the best number of clusters that make sense to my dataset, I used the elbow method.


Results: 
Please refer to my blog:
https://fha5025.wixsite.com/website/post/analyzing-the-consumers-of-starbucks-coffee
