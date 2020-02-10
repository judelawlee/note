## 示例程序运行
    hadoop jar lib/hbase-mapreduce-2.2.2.jar rowcounter stu
    hadoop jar lib/hbase-mapreduce-2.2.2.jar importtsv -Dimporttsv.columns=HBASE_ROW_KEY,info:name,info:color fruit hdfs://master:9000/fruit.tsv