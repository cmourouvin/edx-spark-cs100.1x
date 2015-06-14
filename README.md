# Introduction to Big Data with Apache Spark

Here i will put all my notes about this online course :  https://courses.edx.org/courses/BerkeleyX/CS100.1x/1T2015

My goal is also to learn about #python.

_Note :_ no solution will be posted here :)

## Week1

Just about the installation o start the real course. The installation is based on #vagrant, #virtualbox.

## Week2

Basics about Spark, RDDs.

`Spark program = DRIVER + WORKERS`

RDDs are distributed across workers.

`Tranformations` : *map*, *filter*, *distinct*, *flatMap*

`Actions` : *reduce*, *take*, *collect*, *takeOrdered*

Caching your RDD is essential to speed up you spark program.

You can **transform** a dataset or make an **action** on it.

Shared Variables, 2 types :

- Broadcast variables : read-only value send to all workers
- Accumulators : aggregate value from workers to driver

- __Links__

https://spark.apache.org/docs/latest/programming-guide.html

https://spark.apache.org/docs/latest/api/python/

1TB free dataset from criteo : http://apache-spark-user-list.1001560.n3.nabble.com/Dataset-announcement-td22507.html

## Week3
