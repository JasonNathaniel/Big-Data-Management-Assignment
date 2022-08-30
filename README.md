# Big Data Management and Processing

## Case study
StopFire is a campaign started by Monash University to predict and stop the fire in Victorian cities. They have employed sensors in different cities of Victoria and have collected a large amount of data. The data is so big that their techniques have failed to provide the results on time to predict fire. They have hired us as the data analyst to migrate their data to the NoSQL database (MongoDB). They want us to analyse their data and provide them with results. In addition, they want us to build an application, a complete setup from streaming to storing and analyzing the data for them using Apache Kafka, Apache Spark Streaming and MongoDB.


## Architecture
<img src="Overall architecture.jpg" height = "500">

* Part A
  * Design an embedded data model to support efficient querying of the two dataset
* Part B
  * Implement multiple Apache Kafka producers to simulate real-time streaming which will be processed by Apache Kafka Structured Streaming
  * Managed processed data into Mongo DB and create an interactive map visualisation
