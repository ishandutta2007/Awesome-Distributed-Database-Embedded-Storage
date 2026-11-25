# Awesome-Distributed-Database-Embedded-Storage
# Top Distributed Database & Embedded Storage Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Distributed SQL/NoSQL, Serverless Databases & High-Performance Embedded Storage Engines*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Distributed Databases & Embedded Storage**. These tools power globally distributed transactions, horizontal sharding, serverless compute-storage separation, and ultra-low-latency local persistence for modern applications, cloud infrastructure, and edge devices.

**Examples** include CockroachDB Dedicated, TiDB Cloud, YugabyteDB Managed, Neon Serverless Postgres, PlanetScale, Amazon Aurora Serverless, Google Cloud Spanner, SingleStore Helios, FaunaDB, and Supabase (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom storage engines, and embedded key-value/SQL persistence — ideal for backend engineers, systems programmers, and architects building resilient, vendor-neutral data infrastructure.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[CockroachDB Dedicated](https://cockroachlabs.com)** | Fully managed, single-tenant distributed SQL database engineered for global scale, survivability, and strong ACID consistency. | Starting at **$0.60/hour** (Advanced dedicated tier, min. 4 vCPUs) | **$400 free trial credits** for new cloud organizations (or free-forever Basic serverless tier up to 50M RUs & 10 GiB storage/month). |
| **[TiDB Cloud](https://pingcap.com)** | Fully managed cloud-native HTAP (Hybrid Transactional and Analytical Processing) database service compatible with MySQL. | Starting at **$0.22/hour** (Dedicated tier) / **$400/month** (Essential tier) | **Free forever plan**: up to 5 instances, 250M Request Units (RUs)/month, 25 GiB row storage, and 25 GiB columnar storage. |
| **[YugabyteDB Managed](https://yugabyte.com)** | Fully managed Distributed SQL-as-a-Service built on PostgreSQL-compatible architecture for cloud-native transactional workloads. | Starting at **$0.25/vCPU-hour** (Standard/Professional production tier) | **Free forever Sandbox tier**: 1 cluster, 2 vCPUs, 4 GB RAM, 10 GB storage, and 25 concurrent connections (or 30-day dedicated trial with trial credits). |
| **[Neon Serverless Postgres](https://neon.tech)** | Managed serverless PostgreSQL platform separating storage and compute with instant database branching and scale-to-zero. | Starting at **$0.106/CU-hour** (~$15/month typical spend on Launch tier; 1 CU = 1 vCPU + 4 GB RAM) | **Free forever plan**: up to 100 projects, 100 CU-hours/project/month, 1 GB storage/project (up to 20 GB account total), 10 branches/project, and 5 GB egress/month. |
| **[PlanetScale](https://planetscale.com)** | MySQL-compatible serverless database platform powered by Vitess with non-blocking schema changes and horizontal sharding. | Starting at **$5/month** (single-node dev database) or **$15/month** (PS-5 3-node HA cluster) | **14-day free trial** with access to core platform features and development branches (no permanent free tier; requires paid plan starting at $5/mo). |
| **[Amazon Aurora Serverless](https://amazon.com)** | On-demand, auto-scaling cloud-native relational database engine compatible with MySQL and PostgreSQL. | Starting at **$0.12/ACU-hour** (scales in 0.5 ACU increments; ~$43.20/month at continuous min. 0.5 ACU floor) | **AWS Free Tier credits**: $100–$200 sign-up promotional credits valid for 12 months, with free tier configurations allowing up to 4 ACUs and 1 GiB storage. |
| **[Google Cloud Spanner](https://google.com)** | Globally distributed, strongly consistent relational database service utilizing TrueTime atomic clocks for external consistency. | Starting at **$0.09 per 100 processing units/hour** (~$65/month baseline compute for 100 PUs; $0.90/node-hour) | **90-day free trial instance** with up to 10 GiB database storage and 5 databases (plus $300 GCP sign-up trial credits). |
| **[SingleStore Helios](https://singlestore.com)** | Managed cloud-native distributed SQL database built for ultra-fast real-time analytics and transactional processing. | Starting at **$0.99/hour** (Standard S-00 instance: 2 vCPUs, 16 GB RAM) | **Free forever shared tier**: 1 GB compressed storage (~4 GB uncompressed) with full HTAP & vector engine features (plus $500 free trial credits for Standard clusters). |
| **[FaunaDB (Fauna)](https://fauna.com)** | Globally distributed, serverless document-relational database offering strict serializability and native APIs. | Starting at **$25/month** (historical self-serve entry tier prior to cloud sunset) | **Free tier historical limit**: 5 databases, 1 GB storage, 100K Read Ops, 50K Write Ops, and 500K Compute Ops/month (cloud service sunsetted May 30, 2025; engine open-sourced). |
| **[Supabase](https://supabase.com)** | Managed open-source Firebase alternative built on PostgreSQL with authentication, instant APIs, storage, and edge functions. | Starting at **$25/month** per organization (Pro tier, includes $10 compute credit) | **Free forever plan**: up to 2 active projects, 500 MB database size, 0.5 GB RAM, 1 GB file storage, 50,000 MAUs, 5 GB egress/month, and 500,000 edge function invocations (auto-pauses after 7 days inactivity). |

## Open-Source GitHub Projects

- **[Xodus-Nexus (`domsvoboda/xodus-nexus`)](https://github.com)**  
  High-performance transactional embedded database and storage layer building upon JetBrains Xodus architecture for JVM ecosystems.

- **[CockroachDB](https://github.com)**  
  Open-source distributed SQL database using Raft consensus and Pebble storage for resilient, multi-region ACID transactions.

- **[TiDB](https://github.com)**  
  Open-source distributed HTAP database speaking the MySQL protocol, backed by the TiKV distributed transactional key-value engine.

- **[YugabyteDB](https://github.com)**  
  High-performance open-source distributed SQL database supporting PostgreSQL (YSQL) and Cassandra (YCQL) APIs atop DocDB.

- **[Neon](https://github.com)**  
  Open-source serverless PostgreSQL storage engine decoupling compute from bottomless cloud object storage with copy-on-write branching.

- **[Vitess](https://github.com)**  
  Open-source database clustering system for horizontal sharding of MySQL at massive scale (the open-source core behind PlanetScale).

- **[Supabase Self-Hosted](https://github.com)**  
  Open-source PostgreSQL backend-as-a-service stack featuring GoTrue auth, PostgREST, Realtime, and Studio for self-hosting.

- **[RocksDB](https://github.com)**  
  High-performance embedded persistent key-value storage engine optimized for fast flash and RAM storage using LSM-trees.

- **[SQLite](https://github.com)**  
  The world's most widely deployed self-contained, serverless, zero-configuration, transactional embedded SQL database engine.

- **[libSQL](https://github.com)**  
  Open-contribution fork of SQLite designed for modern edge computing, embedded replicas, and WebAssembly environments.

- **[DuckDB](https://github.com)**  
  In-process analytical (OLAP) SQL database management system optimized for vectorized query execution and Parquet/Arrow files.

- **[FoundationDB](https://github.com)**  
  Distributed, deterministic, transactional key-value store designed to handle massive structured datasets across multi-node clusters.

- **[TiKV](https://github.com)**  
  Graduated CNCF distributed transactional key-value database written in Rust, utilizing Raft consensus and RocksDB storage.

- **[ScyllaDB](https://github.com)**  
  Ultra-low-latency distributed NoSQL wide-column database written in C++ with a shared-nothing, shard-per-core architecture.

- **[SurrealDB](https://github.com)**  
  Scalable, distributed, multi-model document-graph database built in Rust supporting embedded and clustered deployments.

- **[Pebble](https://github.com)**  
  RocksDB-inspired embedded key-value storage engine written in pure Go, built to power CockroachDB's storage layer.

- **[LMDB (Lightning Memory-Mapped Database)](https://github.com)**  
  Ultra-fast, ultra-compact B+tree memory-mapped embedded key-value store providing full ACID compliance with zero-copy reads.

- **[sled](https://github.com)**  
  Modern, lock-free, thread-safe embedded key-value database written in pure Rust for high-concurrency workloads.

- **[redb](https://github.com)**  
  Simple, portable, ACID-compliant embedded key-value store written in pure Rust, inspired by LMDB's copy-on-write B-trees.

- **[BadgerDB](https://github.com)**  
  Fast, embeddable, persistent key-value store written in pure Go using a WiscKey-inspired LSM tree with value-log separation.

- **[Citus](https://github.com)**  
  Open-source PostgreSQL extension transforming standard Postgres into a distributed database with horizontal sharding.

- **[OrioleDB](https://github.com)**  
  Cloud-native storage engine for PostgreSQL eliminating MVCC bloat and supporting S3-tiered storage for modern hardware.

- **[FerretDB](https://github.com)**  
  Open-source document database proxy translating MongoDB wire protocol queries into SQL backed by PostgreSQL or SQLite.

- **[JetBrains Xodus](https://github.com)**  
  Transactional, schema-less embedded database written in Java and Kotlin featuring log-structured storage and MVCC.

### Additional Strong Open-Source Options

- **Rust Embedded Storage Engines** like **[Fjall](https://github.com)** and **[Limbo](https://github.com)** for async I/O and LSM-tree persistence.
- **Distributed Consensus & Metadata Stores** like **[etcd](https://github.com)** and **[bbolt](https://github.com)** for cluster coordination.
- **Distributed Analytical MPP Engines** like **[StarRocks](https://github.com)** and **[Apache Doris](https://github.com)** for real-time OLAP.
- **Database Sharding Middleware** like **[Apache ShardingSphere](https://github.com)** for transparent horizontal scaling.
- **JVM Embedded Engines** like **[MapDB](https://github.com)** and **[H2 Database](https://github.com)** for off-heap and in-memory persistence.

**Frameworks for building custom systems**: Combine **RocksDB** or **Pebble**, **Raft consensus libraries**, **Apache Arrow**, and **PostgreSQL / SQLite** for bespoke distributed storage engines and edge-sync data platforms.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Distributed databases and storage engines require rigorous benchmarking (e.g., Jepsen tests, YCSB) for your specific consistency and durability guarantees.
- Self-hosted open-source databases require proper backup strategies, replication monitoring, and network security hardening.

---

**Made for backend engineers, database architects, systems programmers, and infrastructure teams.**  
Let's make distributed data and embedded storage more open, resilient, and high-performing.

