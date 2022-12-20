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

Start/stop Safe Mode HDFS
```
hdfs dsfadmin -safemode
hdfs dfsadmin -safemode leave
```

Start history server
```
mr-jobhistory-daemon.sh start historyserver
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

Start Pig with mapreduce
```
pig -x mapreduce
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
hdfs dfs -copyFromLocal <origin> <destination>
```

Copy files hdfs -> local
```
hdfs dfs -get <origin> <destination>
```

Delete file hdfs
```
hdfs dfs -rm <file>
```

Format namenode
```
hdfs dfs namenode -format
```

Report dfsadmin
```
hdfs dfsadmin -report
```

Run MapReduce with python
```
python <file.py> hdfs:///mapred/<data> -r hadoop
```
