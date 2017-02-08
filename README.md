# Meetup material for Boston ML Meetup @ Spark Summit East 2017

Requirements:
* `elasticsearch-spark` 2.4.0 JAR on the classpath ([download](https://www.elastic.co/downloads/past-releases/elasticsearch-apache-hadoop-2-4-0)).
* Spark 1.6.x ([download](http://spark.apache.org/downloads.html)).
* Running instance of Elasticsearch 2.4.x ([download](https://www.elastic.co/downloads/past-releases/elasticsearch-2-4-1)).
* ES vector scoring plugin installed (https://github.com/MLnick/elasticsearch-vector-scoring).
* Jupyter (`pip install jupyter`).

To run: 

```
PYSPARK_DRIVER_PYTHON=ipython PYSPARK_DRIVER_PYTHON_OPTS="notebook" PATH_TO_SPARK_1.6/bin/pyspark --driver-memory 2g --driver-class-path PATH_TO_ES_HADOOP/dist/elasticsearch-spark_2.10-2.4.0.jar
```
