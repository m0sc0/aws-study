# RDS
* Automatic Backups!!
* transaction logs every 5 m
* Useful for applications with unpredictable workloads

MultiAZ Master -> StandBy (SYNC replication)
AZ replication Master -> Read Replicas (ASYNC replication)
Cross-region replication is async

# Aurora

Writer endpoint
Reader endpoint with shared volume


# Aurora Serverless
For unpredictable workloads
# Aurora Multimaster
For continuos writes
# Aurora Global
Cross-region read replica
Global DB


DynamoDB

# Elastic Cache
No support iam
## memcache
no tiene nada
## redis
multiaz
read replica
backup&restore
