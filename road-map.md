🏗️ 1. Temel Altyapı & Dev Environment

- `Linux`: Process & Memory Management, I/O Redirection, Shell Scripting, Network/System Performance Tools (htop, netstat, tcpdump, strace).
- `Networking`: TCP/IP stack, HTTP/1.1 vs HTTP/2 vs HTTP/3, Socket Programming, TLS/SSL El Sıkışması, DNS, Load Balancing.
- `Maven / Gradle`: Multi-module proje mimarisi, Dependency Management & Resolution, Custom Plugin/Goal geliştirme, Build Lifecycle optimization.
- `Docker & Containerization`: Multi-stage builds, Container Image Optimization, Rootless Containers, Networking & Volume Driver'ları.

🎨 2. Mimari, Tasarım & Kodlama Prensipleri

- `Domain-Driven Design (DDD)`: Strategic Design (Bounded Context, Context Mapping) ve Tactical Design (Entities, Value Objects, Aggregates, Domain Events).
- `Clean Architecture & Hexagonal Architecture`: Ports and Adapters pattern, Dependency Inversion, Framework-independent domain katmanı.
- `Data-Oriented Programming (DOP)`: Java 17/21+ özellikleri (Records, Sealed Classes/Interfaces, Pattern Matching, Value Objects) ile immutability ve veri merkezli tasarım.
- `Test-Driven Development (TDD)`: Unit Test, Integration Test, Contract Testing (Spring Cloud Contract / Pact), Testcontainers kullanımı.
- `JVM Internals & Concurrency`: Garbage Collection algoritmaları (ZGC, Shenandoah, G1GC), Memory Model (JMM), Thread Pool yönetimi, Virtual Threads (Project Loom) ve Structured Concurrency.

💾 3. Çekirdek Spring Framework & Veri Yönetimi

- `Spring Transactions`: ACID prensipleri, Isolation Levels (Read Committed, Repeatable Read vb.), Propagation Types, Transactional Context yayılımı ve JDBC/R2DBC farkları.
- `Reactive Programming`: Reactive Streams Spesifikasyonu, Project Reactor (Mono/Flux), Backpressure yönetimi, Thread Scheduling (Schedulers).
- `Spring WebFlux`: Non-blocking I/O mimarisi, Event Loop, Reactive WebClient, R2DBC (Reactive Relational Database Connectivity) entegrasyonu.
- `Distributed Caching & CQRS `: Redis mimarisi, Cache Stampede/Eviction stratejileri, Read/Write Segregation, Command Query Responsibility Segregation (CQRS) uygulaması.

🌐 4. Mikroservisler, Haberleşme & Event-Driven Ekosistem

- `Microservices Patterns`: API Gateway, Service Discovery, Circuit Breaker (Resilience4j), Bulkhead, Rate Limiting.
- `gRPC`: Protocol Buffers (.proto), Multiplexing, HTTP/2 taşıma katmanı, Unary & Streaming RPCs, gRPC-Web entegrasyonu.
- `GraphQL`: Schema Design, Queries/Mutations/Subscriptions, Resolvers, N+1 Problemi ve DataLoader çözümleri.
- `Kafka`: Partitioning & Rebalance stratejileri, Consumer Groups, Exactly-Once Semantics (EOS), Log Compaction, Kafka Streams.
- `Event-Driven Spring Boot & Microservices`: Spring Cloud Stream, Event-Driven Architecture (EDA) kalıpları, Event Sourcing.
- `Reactive Event-Driven Microservices`: WebFlux ve Kafka/RabbitMQ ile non-blocking uçtan uca olay mimarisi.
- Dağıtık Veri Tutarlılığı / Distributed Transactions:
   - `Saga Pattern`: Orchestration-based vs Choreography-based Saga.
   - `Transactional Outbox Pattern`: Dual-write probleminin çözümü.
   - `Change Data Capture (CDC)`: Debezium entegrasyonu ile veritabanı olaylarının Kafka'ya akıtılması.

☸️ 5. Orkestrasyon, Dağıtık Sistemler & Observability

- `Kubernetes (K8s)`: Deployments, StatefulSets, Services, Ingress Controllers, ConfigMaps/Secrets, Helm Charts, HPA (Horizontal Pod Autoscaler).
- `OpenTelemetry (OTel)`: Distributed Tracing, Metrics ve Logs toplanması, OTel Collector mimarisi, Jaeger, Prometheus ve Grafana entegrasyonu.
- `API Security & Identity`: OAuth2.0 / OIDC (OpenID Connect), JWT token doğrulama/rotasyon, Service-to-Service güvenlik için Mutual TLS (mTLS).
