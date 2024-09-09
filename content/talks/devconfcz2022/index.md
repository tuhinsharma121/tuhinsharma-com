---
title: "[DEVCONF.CZ 2022] Building data pipelines for Anomaly Detection"
authors:
- admin
event: Devconf CZ 2022
event_url: https://devconfcz2022.sched.com/event/siJK/building-data-pipelines-for-anomaly-detection
location: Virtual


summary: A SOC analyst navigates complex cloud environments with thousands of VMs, containers, and connections daily, and this talk covers high-availability, scalable data pipelines to manage such challenges.
abstract: "Cloud-native applications. Multiple Cloud providers. Hybrid Cloud. 1000s of VMs and containers. Complex network policies. Millions of connections and requests in any given time window. This is the typical situation faced by a Security Operations Control (SOC) Analyst every single day. In this talk, the speaker talks about the high-availability and highly scalable data pipelines."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2022-01-28T18:00:00Z"
date_end: "2022-01-28T18:50:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2022-01-28T00:00:00Z"


tags: 
- devconfcz2022

# Is this a featured talk? (true/false)
featured: false

---

<h3>Description</h3>

Cloud-native applications. Multiple Cloud providers. Hybrid Cloud. 1000s of VMs and containers. Complex network policies. Millions of connections and requests in any given time window. This is the typical situation faced by a Security Operations Control (SOC) Analyst every single day. In this talk, the speaker talks about the high-availability and highly scalable data pipelines that he built for the following use cases :

* Denial of Service: A device in the network stops working.
* Data Loss : An example is a rogue agent in the network transmitting IP data outside the network
* Data Corruption : A device starts sending erroneous data.

The above can be solved through anomaly detection models. The main challenge here is the data engineering pipeline. With almost 7 Billion events occurring every day, processing and storing that for further analysis is a significant challenge. The machine learning models (for anomaly detection) has to be updated every few hours and requires the pipeline to create the feature store in a significantly small time window.
The core components of the data engineering pipeline are:

* Apache Flink
* Apache Kafka
* Apache Pinot
* Apache Spark
* Mlflow
* Apache Superset

The event logs are stored in Pinot through Kafka topic. Pinot supports apache kafka based indexing service for realtime data ingestion. Pinot has primitive capabilities to create sliding time window statistics. More complex real-time statistics are computed using Flink. Apache Flink is a stream-processing engine and provides high throughput and low latency. Spark jobs are used for batch processing. Mlflow is used for machine learning model management. Superset is used for visualization.

The speaker talks through the architectural decisions and shows how to build a modern real-time stream processing data engineering pipeline using the above tools.

Outline
* The problem: overview
* Different Architecture Choices
* The final architecture - a brief explanation
* Real-Time Processing
* Apache Kafka
* Message broker vs Message Queue
* RabitMQ vs Kafka
* Why Kafka?
* Apache Flink
* Micro-batching vs Streaming
* Flink vs Spark Streaming
* Why Flink?
* Apache Pinot
* OLAP vs OLTP
* Why Pinot?
* Batch Processing
* Apache Spark
* Anomaly detection
* Models
* Data Engineering + Machine Learning
* ML and MLLIB
* Mlflow - Model management
* Visualization - Superset
* A short demo


<p>Presentation Video </p>

{{< youtube wdav9Q6wywI >}}