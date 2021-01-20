# Tech Architectures - A Complete Guide

**Motivation**
- Learn the internals of top world class large-scale systems.
- Prep for the system design interview.

**Top Architectures Down Under**
- NGINX
  - [Inside NGINX: How We Designed for Performance & Scale](https://www.nginx.com/blog/inside-nginx-how-we-designed-for-performance-scale/).
  - [NGINX Internals](https://www.aosabook.org/en/nginx.html)

  ```diff
  ! Points To Remember
  1. Why highly scalable : Due to it's event driven architecture.
  ```
  
  ```diff
  ! Usage
  1. Load Balancer
  2. API Gateway
  3. Reverse Proxy Server
  ```
  
  
  ```diff
  ! Important Internals
  1. Event Driven Architecture
  ```

- CASSANDRA
  - [Understanding the architecture of Cassandra](https://docs.datastax.com/en/archived/cassandra/3.0/cassandra/architecture/archTOC.html).
  - [Cassandra Architecture and Write Path Anatomy](https://medium.com/jorgeacetozi/cassandra-architecture-and-write-path-anatomy-51e339bcfe0c)
  ```diff
  ! Points To Remember
  1. Why high write throughput : Cassandra’s peer-to-peer architecture overcomes the limitations of master-slave designs and allows for both high availability and massive scalability.
  ```
  
  ```diff
  ! Usage
  1. In write heavy applications like activity tracking & analytics.
  2. Highly available & scalable applications.
  ```
  ```diff
  ! Important Internals
  1. Peer-to-Peer gossip communication protocol
  2. Partitioners
  3. Data Replication
  4. Commit Logs / SSTable
  ```
  
 - KAFKA
   - [Getting Started with Kafka](https://kafka.apache.org/documentation/#gettingStarted).
  
   ```diff
   ! Usage
   1. Data Pipeline
   2. Log Aggregation
   3. Real Time Streaming
   4. Messaging
   5. Commit Log
   ```
   ```diff
   ! Important Internals
   1. Pub - Sub / Queue Model
   2. Topic & Partition
   3. Producer & Consumer
   4. Data Replication
   5. Kafka Streams
   ```
   
 - Apache Solr / Lucene
   - [Inverted Indexing with Solr](https://towardsdatascience.com/machine-learning-to-big-data-scaling-inverted-indexing-with-solr-ba5b48833fb4).
   - [Learn Solr](https://lucene.apache.org/solr/guide/8_4/solr-tutorial.html)
   - [Building Inverted Index](https://nlp.stanford.edu/IR-book/html/htmledition/a-first-take-at-building-an-inverted-index-1.html)
   - [Analysis of Lucene](https://medium.com/@Alibaba_Cloud/analysis-of-lucene-basic-concepts-5ff5d8b90a53)
   - [Important Basics - Lucene Query Architecture](https://docs.microsoft.com/en-us/azure/search/search-lucene-query-architecture)
  
   ```diff
   ! Usage
   1. Advanced Full Text Search
   2. Server statistics logging
   ```
   ```diff
   ! Important Internals
   1. Inverted Idexing
   ```  



**Top Reads - Company Wise**
- NETFLIX
  - [Evolution of the Netflix Data Pipeline](https://netflixtechblog.com/evolution-of-the-netflix-data-pipeline-da246ca36905)
- UBER
  - [UBER System Design](https://medium.com/@narengowda/uber-system-design-8b2bc95e2cfe)
  
  
  
**Good To Know Reads - Concept Wise**
- Long Polling vs WebSockets vs Server-Sent Events
  - [Long Polling vs WebSockets vs Server-Sent](https://medium.com/system-design-blog/long-polling-vs-websockets-vs-server-sent-events-c43ba96df7c1)
  - [Polling vs SSE vs WebSocket— How to choose the right one](https://codeburst.io/polling-vs-sse-vs-websocket-how-to-choose-the-right-one-1859e4e13bd9)
- Serverless
  - [Serverless and OpenWhisk Architecture](https://www.oreilly.com/library/view/learning-apache-openwhisk/9781492046158/ch01.html)
- Distributed Logging
  - [Using logs to build a solid data infrastructure](https://www.confluent.io/blog/using-logs-to-build-a-solid-data-infrastructure-or-why-dual-writes-are-a-bad-idea/)

