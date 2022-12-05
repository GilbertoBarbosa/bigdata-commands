Version
```
hadoop version
```

Start/stop hadoop service
```
start-dfs.sh
stop-dfs.sh
```

Start/stop yarn service
```
start-yarn.sh
stop-yarn.sh
```

Start/stop zookeeper service
```
zkServer.sh start
zkServer.sh stop
```

Start/stop/shell hbase service
```
start-hbase.sh
stop-hbase.sh
hbase shell
```

Create schema at hive
```
schematool -dbType derby -initSchema
```

Start Hive/Pig
```
hive
pig
```

Check status Hadoop services
```
jps
```

List directory
```
hdfs dfs -ls <path>
```

Create directory
```
hdfs dfs -mkdir <directoryName>
```

Copy files local -> hdfs
```
hdfs dfs -put <origin> <destination>
```

Copy files hdfs -> local
```
hdfs dfs -get <origin> <destination>
```

Format namenode
```
hdfs dfs namenode -format
```

Report dfsadmin
```
hdfs dfsadmin -report
```

