# spark-saturday-advanced


### Instructions to Register for Free Databricks Community Edition

* Go to http://databricks.com/try-databricks

* Start Today for Community Edition.

* Ensure you use an email address from which you can access e-mails.

```
spark.hadoop.io.compression.codecs org.apache.hadoop.io.compress.DefaultCodec,is.hail.io.compress.BGzipCodec,org.apache.hadoop.io.compress.GzipCodec
spark.sql.files.openCostInBytes 1099511627776
spark.sql.files.maxPartitionBytes 1099511627776
spark.hadoop.mapreduce.input.fileinputformat.split.minsize 1099511627776
spark.hadoop.parquet.block.size 1099511627776
spark.driver.extraClassPath ./hail-2_1_1.jar
spark.executor.extraClassPath ./hail-2_1_1.jar
```


### Useful Links

* Hail, the Spark-based genomic analysis software: https://hail.is/

* Spark 2.1.0 documentation: http://spark.apache.org/docs/2.1.0/

* Anaconda documentation: https://docs.continuum.io/anaconda/navigator/tutorials/

* Databricks documentation: http://docs.databricks.com
