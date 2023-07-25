#Network-based IDS
The approach that is used in this paper is based on Penalty Reward-FCM or Fuzzy C- means clustering approach, that can detect an intrusion more effectively, by taking in consideration of deviation of an inbound network from the legit connection. Also, in the proposed model KNN or k-nearest neighbor (Dempster Shafer Theory of Computation) is used to obtain the rule set and optimal one is obtained by applying modified weighted k-nearest algorithm. The experiment has been performed on NSL KDD Train and Test Dataset for validation. The experiment’s final analysis will prove the effectiveness of the proposed system.

# USAGE
1. Clone this repository
2. Make sure you have Java installed
3. To run the PRFCM clustering compile and execute `IntrusionDetectionSystem.java` file
4. To run the FCM clustering compile and execute `FCM.java` file
5. (Optional) In order to re-create the auxillary files use the `NearestNeighbour.java` file
