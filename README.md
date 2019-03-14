# AWS-Spot-Instances-Dataset-Analysis-using-Hadoop-MapReduce-Hive-BigQuery
Data is completely analysed using Hadoop ecosystem. In general, AWS Spot Instances are way cheaper than the AWS On-Demand Instances. So here, we determine the region/Availability Zone which is most stable and has the lowest instance price, i.e. with less number of fluctuations in the AWS pricing, users can worry less about the instances terminating without any prior notice. 

We use the Mapper and Reducer function for the region(stable) and price(low) analysis, create a table in HDFS and load and process the data using Hive query. Spark/Big Query is also used to process the data faster as shown in the BigQuery folder.
