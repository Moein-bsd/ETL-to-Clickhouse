# ETL-to-Clickhouse

![My Image](Images/Data-Artitecture-20241121.png)

### Nodes and Ip address:
| Node       | Service                     | IP     |
|---------------|---------------------------------|------------|
| Node1    | Kafka node1 , CH node1(shard1)     | 192.168.16.240   |
| Node2    | Kafka node2 , CH node2(shard1)    | 192.168.16.241|
| Node3    | Kafka node3 , CH node3(shard2)     | 192.168.16.242    |
| Node4    |  CH node4(shard1)     | 192.168.16.243    |
| Node5    | Apache ZooKeeper , HAProxy    | 192.168.16.244    |
| Node6    | Apache ZooKeeper , HAProxy    | 192.168.16.245    |
| Node7    | Apache ZooKeeper , HAProxy    | 192.168.16.246    |
| Node8    | Apache ZooKeeper , HAProxy    | 192.168.16.247    |

