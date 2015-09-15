# spark-scala
# SqlWordcount example
# Install sbt in your EMR Cluster

```
while true ; do echo "`date`,${RANDOM} "; sleep 1; done | nc -lk 9999
git clone <>

cd SqlWordCount
sbt clean package

spark-submit --master=yarn-client --class org.apache.spark.examples.streaming.SqlNetworkWordCount ~/SqlWordCount/target/scala-2.11/sqlnetworkwordcount_2.11-1.0.jar IPADDRESS 9999
```
