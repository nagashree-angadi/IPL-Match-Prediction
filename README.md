# IPL-Match-Prediction

Built a statistical model to predict the winners of cricket tournament using players statistics and previous matches results. Used k-Means clustering to group batsmen and bowlers. 

The model predicted the winner of matches with an accuracy of about 83%.

# Technologies Used
1. Python
2. Hive
3. Spark

# Steps to Run code

1. Move the Player vs Player data into Spark
2. Run python compute_cluster.py to group similar players into clusters and store in Hive.
3. Run python cluster_vs_cluster.py to compute cluster vs cluster data with probabilities and store in HBase.
4. Store new team members in Team1.txt and Team2.txt
5. Run python IPL.py to simulate the match and predict the winner.

