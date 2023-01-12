# SQS: queue model
* filter by groupid
* message visibility timeout
* 300 msg/s without batching, 3000 msg/s with

# SNS: pub/sub model
* filter by policy
## SNS FIFO + SQS FIFO = FAN OUT
* fan out + ordering + deduplication


# Kinesis: real-time streaming model
Kinesis Data Streams: capture, process, and store data streams  
Kinesis Data Firehose: load data streams into AWS data stores  
* destination: s3, redshift,elasticsearch  
Kinesis Data Analytics: analyze data streams with SQL or Apache Flink  
Kinesis Video Streams: capture, process, and store video streams  

partition key  
