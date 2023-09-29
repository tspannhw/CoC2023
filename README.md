### CoC 2023

Community over Code, Apache NiFi, Apache Kafka, Apache Flink, Python, GTFS, Transit, Open Source, Open Data



![qr](https://github.com/tspannhw/CoC2023/blob/main/coc2023qr.png?raw=true)


### Talks

https://www.slideshare.net/bunkertor/coc23utilizing-realtime-transit-data-for-travel-optimization


### Talk Details

````
Let’s Monitor The Conditions at the Conference
https://communityovercode.org/schedule-list/#IOT001

At home, I monitor the temperature, humidity, gas levels, ozone, air quality, and other features around my desk.
Let’s bring this to the different spots around the conference including lunch tables, vendor booths, hotel rooms, and more. I need to know about these readings now, not when I get back home from the conference. We need to get these sensor readings immediately in case we need to turn on a fan or move to another area. We will also see if my talk produces a lot of hot air!?!??
My setup is pretty simple, a raspberry pi, a breakout garden sensor mount, and as many sensors as I can carry. All code and parameters will be available ASF-licensed in github.
The software stack is Python and Java, MQTT, HTML, JQuery, and Apache NiFi, Apache Kafka and Apache Flink.

Speaker: Timothy J. Spann
Tim Spann is a Principal Developer Advocate in Data In Motion for Cloudera. He works with Apache NiFi, Apache Kafka, Apache Pulsar, Apache Flink, Flink SQL, Apache Pinot, Trino, Apache Iceberg, DeltaLake, Apache Spark, Big Data, IoT, Cloud, AI/DL, machine learning, and deep learning. Tim has over ten years of experience with the IoT, big data, distributed computing, messaging, streaming technologies, and Java programming. Previously, he was a Developer Advocate at StreamNative, Principal DataFlow Field Engineer at Cloudera, a Senior Solutions Engineer at Hortonworks, a Senior Solutions Architect at AirisData, a Senior Field Engineer at Pivotal and a Team Leader at HPE. He blogs for DZone, where he is the Big Data Zone leader, and runs a popular meetup in Princeton & NYC on Big Data, Cloud, IoT, deep learning, streaming, NiFi, the blockchain, and Spark.


Utilizing Real-Time Transit Data for Travel Optimization
https://communityovercode.org/schedule-list/#SG007

There are a lot of factors involved in determining how you can find our way around and avoid delays, bad weather,
dangers and expenses. In this talk I will focus on public transport in the largest transit system in the United States, the MTA,
which is focused around New York City. Utilizing public and semi-public data feeds, this can be extended to most city and
metropolitan areas around the world. As a personal example, I live in New Jersey and this is an extremely useful use of open source and public
data.
Once I am notified that I need to travel to Manhattan, I need to start my data streams flowing. Most of the data sources are REST feeds that are ingested
by Apache NiFi to transform, convert, enrich and finalize it for usage in streaming tables with Flink SQL, but also keep that same contract with Kafka consumers,
Iceberg tables and other users of this data. I do not need to many user interfaces to interopt with the system as I want my final decision sent in a Slack message
to me and then I’ll get moving. Along the way data will be visible in NiFi lineage, Kafka topic views, Flink SQL output, REST output and Iceberg tables.
Apache NiFi, Apache Kafka, Apache OpenNLP,
Apache Tika, Apache Flink, Apache Avro, Apache Parquet, Apache Iceberg

Speaker: Timothy J. Spann
Tim Spann is a Principal Developer Advocate in Data In Motion for Cloudera. He works with Apache NiFi, Apache Kafka, Apache Pulsar, Apache Flink, Flink SQL, Apache Pinot, Trino, Apache Iceberg, DeltaLake, Apache Spark, Big Data, IoT, Cloud, AI/DL, machine learning, and deep learning. Tim has over ten years of experience with the IoT, big data, distributed computing, messaging, streaming technologies, and Java programming. Previously, he was a Developer Advocate at StreamNative, Principal DataFlow Field Engineer at Cloudera, a Senior Solutions Engineer at Hortonworks, a Senior Solutions Architect at AirisData, a Senior Field Engineer at Pivotal and a Team Leader at HPE. He blogs for DZone, where he is the Big Data Zone leader, and runs a popular meetup in Princeton & NYC on Big Data, Cloud, IoT, deep learning, streaming, NiFi, the blockchain, and Spark.



Looking at the New Features of Apache NiFi
https://communityovercode.org/schedule-list/#SG011

Apache NiFi has a lot of new features, processors and best practices that have arrived in the last year or so.
I will walk through building flows using the latest tips, techniques and processor.
I will and change a number of data flows utilizing the latest NiFi version and point out gotchas and some never dos. The deck will act as a take-away with notes, tips and guides to what we covered.

Speaker: Timothy J. Spann
Tim Spann is a Principal Developer Advocate in Data In Motion for Cloudera. He works with Apache NiFi, Apache Kafka, Apache Pulsar, Apache Flink, Flink SQL, Apache Pinot, Trino, Apache Iceberg, DeltaLake, Apache Spark, Big Data, IoT, Cloud, AI/DL, machine learning, and deep learning. Tim has over ten years of experience with the IoT, big data, distributed computing, messaging, streaming technologies, and Java programming. Previously, he was a Developer Advocate at StreamNative, Principal DataFlow Field Engineer at Cloudera, a Senior Solutions Engineer at Hortonworks, a Senior Solutions Architect at AirisData, a Senior Field Engineer at Pivotal and a Team Leader at HPE. He blogs for DZone, where he is the Big Data Zone leader, and runs a popular meetup in Princeton & NYC on Big Data, Cloud, IoT, deep learning, streaming, NiFi, the blockchain, and Spark.


````


### Articles

* https://medium.com/@tspann/open-source-streaming-talks-in-progress-3e75af8848b0
* https://medium.com/cloudera-inc/cdc-not-cat-data-capture-e43713879c03
* https://medium.com/cloudera-inc/finding-the-best-way-around-7491c76ca4cb
* https://medium.com/cloudera-inc/using-apache-nifi-to-backup-and-restore-minifi-flows-from-cloudera-efm-87f303b56ebd
* https://medium.com/cloudera-inc/hbase-to-hbase-via-apache-nifi-d3d1d674eab2
* https://medium.com/cloudera-inc/edge-managing-c-and-java-agents-d6590c963e9c
* https://medium.com/cloudera-inc/watching-airport-traffic-in-real-time-32c522a6e386
* https://medium.com/cloudera-inc/writing-critical-syslog-events-to-apache-iceberg-for-analysis-a0799f24fe18
* https://medium.com/@tspann/apache-nifi-1-22-updates-e658eaff3308
* https://medium.com/cloudera-inc/harnessing-the-power-of-nifi-building-a-seamless-flow-to-ingest-pm2-5-90246393fcab
* https://medium.com/cloudera-inc/seamless-integration-unleashing-the-power-of-real-time-groceries-with-nifi-kafka-flink-and-32d659fe0903
* https://medium.com/cloudera-inc/building-a-real-time-data-pipeline-a-comprehensive-tutorial-on-minifi-nifi-kafka-and-flink-ee03ee6722cb
* https://medium.com/@tspann/using-nifi-as-an-smtp-email-test-server-713677ac5b67
* https://medium.com/@tspann/building-a-travel-advisory-app-with-apache-nifi-in-k8-969b44c84958
* https://medium.com/@tspann/streaming-stocks-with-python-kafka-flink-and-nifi-fbca6be89c87
* https://dzone.com/articles/what-is-a-modern-developer
* https://dzone.com/articles/streaming-change-data-capture-data-two-ways
* https://dzone.com/articles/harnessing-the-power-of-nifi-building-a-seamless-f
* https://dzone.com/trendreports/data-pipelines-2


### Source Code

* https://github.com/tspannhw/mlx-images
* https://github.com/tspannhw/FLaNK-TravelAdvisory
* https://github.com/tspannhw/FLaNK-Halifax
* https://github.com/tspannhw/FLaNK-SaoPauloBrazil
* https://github.com/tspannhw/FLaNK-CDC
* https://github.com/tspannhw/EverythingApacheNiFi
* https://github.com/tspannhw/FLaNK-AircraftTracking
* https://github.com/tspannhw/FLaNK-Edge
* https://github.com/tspannhw/FLaNK-MTA
* https://github.com/tspannhw/NiFi-Man
* https://github.com/tspannhw/FLaNK-ADSB
* https://github.com/tspannhw/FLaNK-Store
* https://github.com/tspannhw/flank-airquality
* https://github.com/tspannhw/FLaNK-Py-VOC-Sensors
* https://github.com/tspannhw/Flow-SGP30-MLX90640
* https://github.com/tspannhw/FLiP-Current22-LetsMonitorAllTheThings



### Info

#### October 8, 2023: Streaming Track, Room 102 

* https://communityovercode.org/schedule/#Oct8 

* https://communityovercode.org/schedule-list/#SG007 

* https://communityovercode.org/schedule-list/#SG011

#### October 10, 2023: Internet of Things Track, Room 109 

* https://communityovercode.org/schedule/#Oct10 

* https://communityovercode.org/schedule-list/#IOT001

