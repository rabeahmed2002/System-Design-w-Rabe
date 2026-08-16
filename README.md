# System Design

A long-term, structured knowledge base for learning, practicing, implementing,
and revising System Design and Distributed Systems.

The goal of this repository is to build a deep understanding of how large-scale
software systems are designed, built, scaled, secured, monitored, and operated.

---

## 🎯 Goals

This repository is built around four goals:

1. Understand System Design fundamentals deeply.
2. Understand how large-scale distributed systems work.
3. Practice designing real-world systems.
4. Prepare for senior-level / MAANG system design interviews.

---

# 🗺️ Repository Map

| Directory | Purpose |
|---|---|
| `00-foundations` | Core System Design fundamentals |
| `01-requirements` | Requirements gathering and capacity estimation |
| `02-networking` | Networking fundamentals and protocols |
| `03-api-design` | REST, gRPC, API design and communication |
| `04-databases` | SQL, NoSQL, indexing, replication, sharding |
| `05-caching` | Caching strategies and distributed caches |
| `06-messaging` | Queues, Kafka, Pub/Sub and event-driven systems |
| `07-distributed-systems` | CAP, consensus, replication and distributed computing |
| `08-scalability` | Horizontal/vertical scaling and bottleneck analysis |
| `09-reliability` | Availability, fault tolerance and disaster recovery |
| `10-security` | Authentication, authorization and system security |
| `11-storage` | Object, block, file and distributed storage |
| `12-microservices` | Microservice architecture and communication |
| `13-system-patterns` | Common architecture and distributed-system patterns |
| `14-observability` | Logging, metrics, tracing and monitoring |
| `15-cloud-architecture` | AWS, GCP, Azure and cloud architectures |
| `16-containers-and-orchestration` | Docker, Kubernetes and orchestration |
| `17-data-intensive-systems` | Streaming, pipelines, search and analytics |
| `18-real-world-systems` | Designs of real-world applications |
| `19-interview-system-design` | Interview preparation and frameworks |
| `20-design-exercises` | System design practice problems |
| `21-implementations` | Implement important distributed-system components |
| `22-diagrams` | Central diagram collection |
| `23-books` | Notes organized by books |
| `24-resources` | Articles, videos, papers and courses |
| `25-cheat-sheets` | Quick revision material |
| `26-projects` | End-to-end system design projects |
| `99-mental-models` | Personal understanding and decision frameworks |

---

# 🧱 Core Topics

## Foundations

- What is System Design?
- High-level design vs low-level design
- Functional requirements
- Non-functional requirements
- Scalability
- Availability
- Reliability
- Performance
- Latency
- Throughput
- Consistency
- Fault tolerance
- CAP theorem
- Trade-offs
- Bottleneck identification

---

# 🌐 Networking

- OSI model
- TCP/IP
- TCP
- UDP
- HTTP/1.1
- HTTP/2
- HTTP/3
- TLS
- DNS
- IP addressing
- Subnetting
- Routing
- NAT
- Proxies
- Reverse proxies
- Load balancers
- CDNs
- WebSockets
- gRPC
- Service discovery

---

# 🔌 API Design

- REST
- HTTP methods
- HTTP status codes
- API versioning
- Pagination
- Filtering
- Sorting
- Authentication
- Authorization
- Rate limiting
- Idempotency
- Webhooks
- gRPC
- GraphQL
- API gateways

---

# 🗄️ Databases

## Relational Databases

- SQL
- Tables
- Primary keys
- Foreign keys
- Indexes
- B-Trees
- Composite indexes
- Normalization
- Denormalization
- Transactions
- ACID
- Isolation levels
- Locks
- Deadlocks
- Query optimization

## NoSQL

- Key-value databases
- Document databases
- Wide-column databases
- Graph databases

## Distributed Databases

- Replication
- Sharding
- Partitioning
- Leader/follower
- Multi-leader
- Leaderless
- Quorum
- Consistent hashing
- Read replicas

## Consistency

- Strong consistency
- Eventual consistency
- Causal consistency
- Read-your-writes
- Consistency models

---

# ⚡ Caching

- Why caching?
- Cache hit/miss
- Cache-aside
- Read-through
- Write-through
- Write-behind
- TTL
- Cache invalidation
- Eviction policies
- LRU
- LFU
- Distributed caching
- Redis
- Memcached
- Hot keys
- Cache stampede
- Cache penetration

---

# 📨 Messaging

- Message queues
- Pub/Sub
- Event-driven architecture
- Kafka
- RabbitMQ
- Producers
- Consumers
- Consumer groups
- Partitions
- Ordering
- Delivery semantics
- At-most-once
- At-least-once
- Exactly-once
- Retries
- Dead-letter queues
- Backpressure
- Event sourcing

---

# 🌎 Distributed Systems

- Distributed system fundamentals
- CAP theorem
- PACELC
- Network partitions
- Replication
- Leader election
- Consensus
- Raft
- Paxos
- Quorum
- Distributed locks
- Logical clocks
- Vector clocks
- Gossip protocols
- Failure detection
- Split brain
- Idempotency
- Exactly-once processing

---

# 📈 Scalability

- Vertical scaling
- Horizontal scaling
- Stateless services
- Stateful services
- Load balancing
- Database scaling
- Read scaling
- Write scaling
- Replication
- Sharding
- Partitioning
- Consistent hashing
- Autoscaling
- Hotspots
- Bottlenecks
- Backpressure

---

# 🛡️ Reliability

- Availability
- Reliability
- Fault tolerance
- Redundancy
- Failover
- Disaster recovery
- Backups
- Replication
- Health checks
- Retries
- Timeouts
- Circuit breakers
- Bulkheads
- Graceful degradation
- Graceful shutdown
- SLA
- SLI
- SLO
- RTO
- RPO

---

# 🔐 Security

- Authentication
- Authorization
- OAuth
- JWT
- Sessions
- Encryption
- Hashing
- TLS
- Secrets management
- Key management
- API security
- Rate limiting
- DDoS protection
- Zero trust
- Common vulnerabilities

---

# 💾 Storage

- Block storage
- File storage
- Object storage
- Distributed storage
- Replication
- Erasure coding
- Metadata
- Consistency
- Distributed file systems
- S3 architecture

---

# 🧩 Microservices

- Monolith
- Modular monolith
- Microservices
- Service boundaries
- Domain-driven design
- Service communication
- Synchronous communication
- Asynchronous communication
- Service discovery
- API gateway
- Distributed transactions
- Saga pattern
- Circuit breaker
- Observability
- Deployment strategies

---

# 🏗️ System Design Patterns

- Load balancer
- Reverse proxy
- API gateway
- Cache-aside
- Pub/Sub
- Message queue
- Event sourcing
- CQRS
- Saga
- Outbox pattern
- Sidecar
- Strangler Fig
- Bulkhead
- Circuit breaker
- Retry
- Rate limiter
- Consistent hashing

---

# 📊 Observability

- Logging
- Metrics
- Tracing
- Distributed tracing
- Monitoring
- Alerting
- Prometheus
- Grafana
- ELK
- OpenTelemetry
- Dashboards

---

# ☁️ Cloud Architecture

## AWS

- EC2
- ECS
- EKS
- Lambda
- S3
- RDS
- DynamoDB
- ElastiCache
- SQS
- SNS
- MSK
- API Gateway
- CloudFront
- Route 53
- VPC

## Other Clouds

- GCP
- Azure
- Multi-region
- Multi-cloud
- Disaster recovery

---

# 🐳 Containers & Kubernetes

- Docker
- Container runtimes
- Kubernetes
- Pods
- Deployments
- StatefulSets
- Services
- Ingress
- Service discovery
- Kubernetes networking
- Autoscaling
- Service mesh
- Container orchestration

---

# 📊 Data-Intensive Systems

- Data pipelines
- Batch processing
- Stream processing
- Search systems
- Indexing
- Analytics
- Data lakes
- Data warehouses
- Recommendation systems
- News feeds
- Ranking systems

---

# 🏢 Real-World System Designs

Systems to design from scratch:

- URL shortener
- Pastebin
- Twitter
- Instagram
- YouTube
- Netflix
- Uber
- WhatsApp
- Google Drive
- Dropbox
- Facebook News Feed
- Amazon
- Airbnb
- Ticket booking
- Payment system
- Notification system
- Chat system
- Ride sharing
- Food delivery
- Job scheduler
- Distributed file storage
- Search engine

---

# 🎯 System Design Interview Framework

For every interview problem:

## 1. Requirements

- Functional requirements
- Non-functional requirements
- Scope
- Assumptions

## 2. Estimation

- Users
- Requests per second
- Read/write ratio
- Storage
- Bandwidth
- Peak traffic

## 3. API Design

- Endpoints
- Request/response
- Authentication
- Idempotency

## 4. Data Model

- Entities
- Relationships
- Database choice
- Indexes

## 5. High-Level Architecture

- Clients
- Load balancer
- API gateway
- Services
- Cache
- Databases
- Message queues
- Object storage

## 6. Deep Dive

Identify the most difficult/scalable components.

## 7. Bottlenecks

- CPU
- Memory
- Network
- Database
- Cache
- Storage
- Queue

## 8. Reliability

- Failures
- Replication
- Failover
- Backups
- Disaster recovery

## 9. Trade-offs

Always explain:

> Why this solution instead of the alternative?

---

# 📚 Books

Primary books:

### Designing Data-Intensive Applications

Focus:

- Storage
- Databases
- Replication
- Partitioning
- Transactions
- Consistency
- Distributed systems
- Stream processing

### System Design Interview — Alex Xu

Focus:

- Interview methodology
- High-level architecture
- Real-world system designs
- Scalability
- Trade-offs

### Grokking System Design

Focus:

- Interview patterns
- Common system designs
- Practical architecture

---

# 💻 Implementations

Important components to implement:

- Load balancer
- Consistent hashing
- Rate limiter
- Distributed lock
- Cache
- Message queue
- Job scheduler
- URL shortener
- Notification service
- API gateway
- Distributed counter

Implementations should preferably include:

- Source code
- README
- Architecture diagram
- Tests
- Benchmark
- Trade-offs
- Failure scenarios

---

# 🧪 Design Exercises

Difficulty:

- Beginner
- Intermediate
- Advanced
- Open-ended

For every exercise document:

1. Requirements
2. Assumptions
3. Capacity estimation
4. APIs
5. Data model
6. Architecture
7. Deep dive
8. Scaling
9. Reliability
10. Security
11. Bottlenecks
12. Trade-offs
13. Possible improvements

---

# 🧠 Mental Models

The `99-mental-models` directory contains my personal understanding.

Examples:

- When should I use SQL vs NoSQL?
- When should I use caching?
- When should I use Kafka?
- When should I use synchronous communication?
- When should I use asynchronous communication?
- When do I need sharding?
- When do I need replication?
- When should I use eventual consistency?
- When do I need a CDN?
- When do I need an API gateway?
- When should I use microservices?
- How do I find system bottlenecks?

These should be short and easy to revise.

---

# 📈 Learning Workflow

For every new concept:

```text
Learn
  ↓
Take notes
  ↓
Understand the internals
  ↓
Draw diagram
  ↓
Find real-world usage
  ↓
Implement if practical
  ↓
Document trade-offs
  ↓
Solve design problem
  ↓
Add interview questions
  ↓
Create cheat sheet
  ↓
Add mental model