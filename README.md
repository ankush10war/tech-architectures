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
