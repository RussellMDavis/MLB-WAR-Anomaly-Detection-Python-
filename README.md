# MLB-WAR-Anomaly-Detection-Python-

This project was a brief investigation of WAR changes pre-, during, and post-steroid era.

My thesis assumed the following:
* Not all players use steroids
* Some benefit from it more than others (see: Barry Bonds)

Given these assumptions, I proposed that there should be more anomalous performances before the steroid era (assuming there was unpublicized steroid use)
and during the steroid era, but less after the steroid era when drug testing became more stringent.

The analysis relies on "robust z-score", which mimics the standard z-score but uses median and median absolute deviation for metrics. 
The base analysis was for All-Star caliber players, representing the top 10% of players.  A second analysis was performed for MVP-caliber players, representing the top 10 players. 

Graphs were generated using matplotlib; an example is shown below.
They display the anomaly score for each individual in each set of data.  The vertical dotted line on each graph
shows the relevant line of demarcation (90th percentile or top 10 individuals) and the associated WAR at that point. 


My findings are presented in the Word document and summarized as follows:
* Surprisingly, the steroid and post-steroid eras showed an overall reduction in WAR in terms of overall performance, individual careers, and players over the age of 32.
* The z-scores for the top 10 performers during the steroid and post-steroid eras, lending credence to my hypothesis about the impact of steroids.