# Grouping IPL Cricketers -  Clustering
- In this project, I use data from the IPL 2023 along with a k-means clustering algorithm to split players into different categories depending on stats like the number of wickets they got and the number of runs they scored.
- The data used in this project comes from [Kaggle](https://www.kaggle.com/datasets/purnend26/ipl-2023-dataset).
- In particular, I was interested in determining which players had a good IPL with the ball and which had a good IPL with the bat. This required concatenation of the bowling and batting datasets using an inner join.
- Using sklearn's KMeans clustering algorithm I was able to cluster the players into three groups according to runs scored and wickets taken. Roughly the clusters were those who scored more than 200 runs, those with more than 8 wickets and those with less than 8 wickets and less than 200 runs. From here we can work out using the data frame which players did well with the bat and which players did well with the ball in particular. Using Seaborn's hue feature I could then visualise the results.

![](Picture_4.png)

- Next, I did the same but for the outer joint.
- Here the clusters are roughly those who scored more than 200 runs, those with more than 6 wickets and those with less than 6 wickets and less than 200 runs. 

![](Picture_5.png)

- This is an interesting visualisation of how players played in the IPL 2023.
- There are plenty more things that I could do with this dataset. Including working out which players had the most impact in the tournament.
- If there are similar datasets from previous years then these could be used to see how players have performed across multiple IPLs.
- These sorts of projects could be used by sports trading companies to help inform their trades for other tournaments.
