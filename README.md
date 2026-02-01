# 🎯 Complete Skills Roadmap for Big Tech Data Engineer (2027)

## 📊 Skills Overview Matrix

| Category | Current Level | Target Level | Priority | Time to Learn |
|----------|---------------|--------------|----------|---------------|
| **DSA & Problem Solving** | Very Basic | Interview Ready | 🔴 Critical | 6-8 months |
| **SQL** | Basic | Expert | 🔴 Critical | 2-3 months |
| **Python** | Basic | Advanced | 🔴 Critical | 3-4 months |
| **Spark** | Basic | Expert | 🔴 Critical | 3-4 months |
| **System Design** | None | Strong | 🔴 Critical | 4-6 months |
| **Kafka/Streaming** | None | Proficient | 🟡 High | 2-3 months |
| **Airflow/Orchestration** | None | Proficient | 🟡 High | 1-2 months |
| **Data Modeling** | Basic | Advanced | 🟡 High | 2 months |
| **Cloud (Multi)** | Azure only | Azure + AWS/GCP | 🟡 High | 2-3 months |
| **dbt** | None | Proficient | 🟢 Medium | 1 month |
| **Docker/K8s** | None | Basic | 🟢 Medium | 1 month |
| **Communication** | Average | Excellent | 🟡 High | Ongoing |

---

## 1️⃣ DATA STRUCTURES & ALGORITHMS (DSA)

### **Why Critical for Big Tech?**
> 35-40% of your interview score. No DSA = No offer.

### **Topics to Master**

```
FUNDAMENTALS (Month 1-2)
├── Time & Space Complexity
│   ├── Big O notation
│   ├── Best/Worst/Average case
│   └── Amortized analysis
│
├── Arrays & Strings
│   ├── Traversal patterns
│   ├── In-place modifications
│   ├── Prefix sums
│   └── String manipulation
│
├── Hash Tables
│   ├── Hash functions
│   ├── Collision handling
│   ├── Frequency counting
│   └── Two-sum patterns
│
└── Two Pointers & Sliding Window
    ├── Opposite direction pointers
    ├── Same direction pointers
    ├── Fixed window
    └── Variable window

CORE DATA STRUCTURES (Month 2-4)
├── Linked Lists
│   ├── Singly/Doubly linked
│   ├── Fast/Slow pointers
│   ├── Reversal techniques
│   └── Merge operations
│
├── Stacks & Queues
│   ├── LIFO/FIFO operations
│   ├── Monotonic stack
│   ├── Expression evaluation
│   └── BFS with queues
│
├── Trees
│   ├── Binary Tree traversals (DFS)
│   ├── Level order (BFS)
│   ├── BST operations
│   ├── Tree construction
│   └── Lowest Common Ancestor
│
├── Heaps / Priority Queues
│   ├── Min/Max heap
│   ├── Heap operations
│   ├── Top-K problems
│   └── Median finding
│
└── Graphs
    ├── Representations (adj list/matrix)
    ├── BFS/DFS traversal
    ├── Connected components
    ├── Cycle detection
    └── Topological sort

ADVANCED PATTERNS (Month 4-6)
├── Binary Search
│   ├── Classic binary search
│   ├── Search in rotated array
│   ├── Search space problems
│   └── Boundary finding
│
├── Dynamic Programming
│   ├── Memoization vs Tabulation
│   ├── 1D DP (Fibonacci, Stairs)
│   ├── 2D DP (Grid, LCS)
│   ├── Knapsack variants
│   ├── String DP
│   └── State machine DP
│
├── Backtracking
│   ├── Permutations/Combinations
│   ├── Subsets
│   ├── N-Queens pattern
│   └── Constraint satisfaction
│
├── Advanced Graphs
│   ├── Dijkstra's algorithm
│   ├── Bellman-Ford
│   ├── Union-Find (DSU)
│   └── Minimum Spanning Tree
│
└── Tries
    ├── Insert/Search
    ├── Prefix matching
    └── Word search problems
```

### **Target Metrics**
| Metric | Target |
|--------|--------|
| Total Problems | 300-350 |
| Easy | 60 (20%) |
| Medium | 210 (60%) |
| Hard | 70 (20%) |
| Solve time (Medium) | < 25 min |

---

## 2️⃣ SQL (Data Engineer's Core Skill)

### **Why Critical?**
> Every DE interview has SQL rounds. Big Tech asks complex analytical queries.

### **Topics to Master**

```
FUNDAMENTALS
├── SELECT, WHERE, ORDER BY, LIMIT
├── JOINs (INNER, LEFT, RIGHT, FULL, CROSS)
├── GROUP BY, HAVING
├── DISTINCT, UNION, INTERSECT
└── NULL handling (COALESCE, NULLIF)

INTERMEDIATE
├── Subqueries
│   ├── Scalar subqueries
│   ├── Correlated subqueries
│   └── EXISTS vs IN
│
├── Common Table Expressions (CTEs)
│   ├── Basic CTEs
│   ├── Multiple CTEs
│   └── Recursive CTEs
│
└── CASE statements
    ├── Simple CASE
    ├── Searched CASE
    └── CASE in aggregations

ADVANCED (Big Tech Focus)
├── Window Functions ⭐⭐⭐⭐⭐
│   ├── ROW_NUMBER, RANK, DENSE_RANK
│   ├── LAG, LEAD
│   ├── FIRST_VALUE, LAST_VALUE
│   ├── SUM/AVG/COUNT OVER
│   ├── PARTITION BY
│   ├── ORDER BY in windows
│   ├── ROWS vs RANGE
│   └── Running totals/Moving averages
│
├── Date/Time Functions
│   ├── DATE_TRUNC, DATE_PART
│   ├── DATEDIFF, DATEADD
│   ├── Time zone handling
│   └── Calendar table patterns
│
├── String Functions
│   ├── CONCAT, SUBSTRING
│   ├── REGEXP patterns
│   └── String aggregation
│
└── Advanced Patterns
    ├── Self joins
    ├── Anti-joins (NOT EXISTS)
    ├── Pivoting/Unpivoting
    ├── Gap and island problems
    ├── Sessionization
    └── Funnel analysis

PERFORMANCE & OPTIMIZATION
├── Query execution plans
├── Index usage
├── Partitioning strategies
├── Query hints
└── Cost-based optimization
```

### **Practice Platforms**
| Platform | Focus | Cost |
|----------|-------|------|
| StrataScratch | Big Tech questions | Free/Paid |
| DataLemur | DE-specific | Free |
| LeetCode Database | Variety | Free |
| HackerRank SQL | Basics | Free |

### **Target: 150+ SQL problems solved**

---

## 3️⃣ PYTHON (Production Grade)

### **Why Critical?**
> Primary language for Data Engineering. Coding interviews often in Python.

### **Topics to Master**

```
CORE PYTHON
├── Data Types & Structures
│   ├── Lists, Tuples, Sets, Dicts
│   ├── List/Dict comprehensions
│   ├── Generators & Iterators
│   └── Collections module
│       ├── defaultdict
│       ├── Counter
│       ├── deque
│       └── OrderedDict
│
├── Functions
│   ├── *args, **kwargs
│   ├── Lambda functions
│   ├── Decorators
│   ├── Closures
│   └── Functools (map, filter, reduce)
│
├── Object-Oriented Programming
│   ├── Classes & Objects
│   ├── Inheritance
│   ├── Polymorphism
│   ├── Encapsulation
│   ├── Abstract classes
│   ├── Dunder methods
│   └── Properties
│
└── Error Handling
    ├── Try/Except/Finally
    ├── Custom exceptions
    └── Context managers

INTERMEDIATE PYTHON
├── Type Hints
│   ├── Basic annotations
│   ├── typing module
│   ├── Optional, Union
│   └── Generics
│
├── Testing
│   ├── pytest basics
│   ├── Fixtures
│   ├── Mocking
│   ├── Parametrized tests
│   └── Test coverage
│
├── Code Quality
│   ├── PEP 8 style guide
│   ├── Linting (pylint, flake8)
│   ├── Black formatter
│   └── Type checking (mypy)
│
└── File Operations
    ├── Reading/Writing files
    ├── CSV, JSON, YAML
    ├── Pathlib
    └── Working with APIs

DATA ENGINEERING PYTHON
├── Pandas
│   ├── DataFrames operations
│   ├── GroupBy operations
│   ├── Merge/Join
│   ├── Window functions
│   ├── Memory optimization
│   └── Vectorization
│
├── Data Validation
│   ├── Pydantic
│   ├── Dataclasses
│   └── Schema validation
│
├── Async Programming
│   ├── asyncio basics
│   ├── async/await
│   └── Concurrent processing
│
└── CLI Development
    ├── argparse
    ├── Click
    └── Typer
```

### **Key Libraries to Know**
| Library | Purpose | Priority |
|---------|---------|----------|
| pandas | Data manipulation | High |
| pyspark | Spark Python API | High |
| pytest | Testing | High |
| pydantic | Data validation | Medium |
| requests | API calls | Medium |
| boto3 | AWS SDK | Medium |
| sqlalchemy | Database ORM | Medium |

---

## 4️⃣ APACHE SPARK (Deep Expertise Required)

### **Why Critical?**
> The #1 skill for Big Tech DE. You claim Spark experience, must be expert level.

### **Topics to Master**

```
SPARK FUNDAMENTALS
├── Architecture
│   ├── Driver & Executors
│   ├── Cluster managers (YARN, K8s, Standalone)
│   ├── SparkContext & SparkSession
│   └── Application lifecycle
│
├── RDD (Conceptual)
│   ├── Transformations vs Actions
│   ├── Lazy evaluation
│   ├── Lineage & DAG
│   └── Partitioning
│
└── DataFrames & Datasets
    ├── Creating DataFrames
    ├── Schema definition
    ├── Column operations
    └── SQL integration

SPARK SQL & DATAFRAME API
├── Transformations
│   ├── select, filter, where
│   ├── withColumn, drop
│   ├── groupBy, agg
│   ├── join (all types)
│   ├── union, intersect
│   └── pivot, unpivot
│
├── Window Functions
│   ├── row_number, rank
│   ├── lag, lead
│   ├── Running aggregations
│   └── Partitioning windows
│
├── Built-in Functions
│   ├── String functions
│   ├── Date/Time functions
│   ├── Array functions
│   ├── Map functions
│   └── JSON functions
│
└── UDFs
    ├── Python UDFs
    ├── Pandas UDFs
    └── Performance implications

SPARK INTERNALS ⭐⭐⭐⭐⭐
├── Catalyst Optimizer
│   ├── Logical plan
│   ├── Physical plan
│   ├── Optimization rules
│   └── Explain plans
│
├── Tungsten Engine
│   ├── Memory management
│   ├── Cache-aware computation
│   └── Code generation
│
├── Shuffle Operations
│   ├── Why shuffle is expensive
│   ├── Shuffle partitions
│   ├── Sort-merge join vs Broadcast
│   └── Shuffle spill
│
└── Memory Management
    ├── Storage memory
    ├── Execution memory
    ├── User memory
    └── OOM troubleshooting

PERFORMANCE TUNING ⭐⭐⭐⭐⭐
├── Data Skew Handling
│   ├── Salting
│   ├── Broadcast joins
│   └── Adaptive Query Execution
│
├── Optimization Techniques
│   ├── Partition pruning
│   ├── Predicate pushdown
│   ├── Column pruning
│   ├── Bucketing
│   └── Caching strategies
│
├── Configuration Tuning
│   ├── Executor memory/cores
│   ├── Driver memory
│   ├── spark.sql.shuffle.partitions
│   ├── spark.default.parallelism
│   └── Dynamic allocation
│
└── Debugging
    ├── Spark UI analysis
    ├── Stage/Task analysis
    ├── GC tuning
    └── Log analysis

SPARK STREAMING
├── Structured Streaming
│   ├── Input sources
│   ├── Output sinks
│   ├── Triggers
│   ├── Watermarking
│   └── Output modes
│
├── Stateful Processing
│   ├── Window operations
│   ├── Sessionization
│   └── Arbitrary state
│
└── Exactly-once Semantics
    ├── Checkpointing
    ├── Idempotent sinks
    └── Transaction support
```

### **Common Interview Questions**
```
1. Explain Spark's lazy evaluation and why it matters
2. How does shuffle work? How to minimize it?
3. Broadcast join vs Sort-merge join - when to use?
4. How to handle data skew in Spark?
5. Explain AQE (Adaptive Query Execution)
6. How to optimize a slow Spark job?
7. Difference between cache() and persist()?
8. What happens during a shuffle?
9. Explain Catalyst optimizer stages
10. How to read Spark execution plans?
```

---

## 5️⃣ SYSTEM DESIGN (For Data Engineers)

### **Why Critical?**
> 30% of interview weight. Shows you can think at scale.

### **Topics to Master**

```
DISTRIBUTED SYSTEMS FUNDAMENTALS
├── CAP Theorem
│   ├── Consistency
│   ├── Availability
│   ├── Partition Tolerance
│   └── Real-world tradeoffs
│
├── Consistency Models
│   ├── Strong consistency
│   ├── Eventual consistency
│   ├── Causal consistency
│   └── Read-your-writes
│
├── Distributed Data
│   ├── Partitioning strategies
│   │   ├── Hash partitioning
│   │   ├── Range partitioning
│   │   └── Consistent hashing
│   │
│   ├── Replication
│   │   ├── Leader-follower
│   │   ├── Multi-leader
│   │   └── Leaderless
│   │
│   └── Consensus
│       ├── Raft
│       └── Paxos (conceptual)
│
└── Fault Tolerance
    ├── Failure modes
    ├── Retry strategies
    ├── Circuit breakers
    └── Idempotency

DATA STORAGE SYSTEMS
├── OLTP vs OLAP
│   ├── Characteristics
│   ├── Use cases
│   └── Design differences
│
├── Storage Formats
│   ├── Row vs Column storage
│   ├── Parquet deep dive
│   ├── ORC
│   ├── Avro
│   └── Delta Lake format
│
├── Index Structures
│   ├── B-Trees
│   ├── LSM Trees
│   ├── Bloom filters
│   └── Z-ordering
│
└── Data Warehouses
    ├── Snowflake architecture
    ├── BigQuery architecture
    ├── Redshift architecture
    └── Synapse architecture

DATA PROCESSING PATTERNS
├── Batch Processing
│   ├── MapReduce model
│   ├── Spark batch
│   └── Workflow patterns
│
├── Stream Processing
│   ├── Event time vs Processing time
│   ├── Windowing
│   ├── Watermarks
│   ├── Exactly-once semantics
│   └── Lambda vs Kappa
│
├── Data Pipeline Patterns
│   ├── ETL vs ELT
│   ├── Change Data Capture
│   ├── Event sourcing
│   └── CQRS
│
└── Data Quality
    ├── Schema evolution
    ├── Data validation
    ├── Data lineage
    └── Data observability

DESIGN PROBLEMS TO PRACTICE
├── Design Data Pipeline at Scale
│   └── Focus: Reliability, monitoring, backfill
│
├── Design Data Warehouse
│   └── Focus: Modeling, partitioning, query patterns
│
├── Design Real-time Analytics System
│   └── Focus: Streaming, aggregations, latency
│
├── Design CDC Pipeline
│   └── Focus: Ordering, exactly-once, schema changes
│
├── Design Feature Store
│   └── Focus: Online/offline, point-in-time
│
├── Design Data Lake
│   └── Focus: Organization, governance, performance
│
├── Design Log Analytics System
│   └── Focus: Ingestion, indexing, querying
│
└── Design Metrics/Alerting System
    └── Focus: Time series, anomaly detection
```

---

## 6️⃣ KAFKA & STREAMING

### **Topics to Master**

```
KAFKA FUNDAMENTALS
├── Architecture
│   ├── Brokers, Topics, Partitions
│   ├── Producers & Consumers
│   ├── Consumer Groups
│   ├── Zookeeper / KRaft
│   └── Replication
│
├── Producers
│   ├── Partitioner strategies
│   ├── Acks configuration
│   ├── Batching & compression
│   └── Idempotent producers
│
├── Consumers
│   ├── Consumer groups
│   ├── Offset management
│   ├── Rebalancing
│   └── Exactly-once consumption
│
└── Operations
    ├── Topic configuration
    ├── Retention policies
    ├── Compaction
    └── Monitoring

KAFKA ECOSYSTEM
├── Kafka Connect
│   ├── Source connectors
│   ├── Sink connectors
│   └── SMT (Transformations)
│
├── Schema Registry
│   ├── Schema evolution
│   ├── Compatibility modes
│   └── Avro/JSON Schema
│
└── Kafka Streams (basics)
    ├── KStream vs KTable
    ├── Joins
    └── Windowing
```

---

## 7️⃣ ORCHESTRATION (Airflow)

### **Topics to Master**

```
AIRFLOW FUNDAMENTALS
├── Core Concepts
│   ├── DAGs
│   ├── Tasks & Operators
│   ├── Sensors
│   ├── Hooks
│   └── XComs
│
├── Operators
│   ├── BashOperator
│   ├── PythonOperator
│   ├── SparkSubmitOperator
│   ├── Custom operators
│   └── Cloud operators
│
├── DAG Design
│   ├── Dependencies
│   ├── Branching
│   ├── Dynamic DAGs
│   ├── TaskGroups
│   └── SubDAGs (deprecated)
│
└── Best Practices
    ├── Idempotency
    ├── Parameterization
    ├── Testing DAGs
    ├── Error handling
    └── Alerting
```

---

## 8️⃣ DATA MODELING

### **Topics to Master**

```
DIMENSIONAL MODELING (Kimball)
├── Fact Tables
│   ├── Transaction facts
│   ├── Periodic snapshot facts
│   └── Accumulating snapshot facts
│
├── Dimension Tables
│   ├── Conformed dimensions
│   ├── Role-playing dimensions
│   ├── Junk dimensions
│   └── Degenerate dimensions
│
├── Slowly Changing Dimensions
│   ├── SCD Type 1 (Overwrite)
│   ├── SCD Type 2 (History)
│   ├── SCD Type 3 (Previous value)
│   └── Hybrid approaches
│
└── Star vs Snowflake Schema

DATA VAULT 2.0
├── Hubs
├── Links
├── Satellites
└── When to use

MODERN APPROACHES
├── One Big Table (OBT)
├── Activity Schema
├── Wide tables
└── Lakehouse patterns
```

---

## 9️⃣ CLOUD PLATFORMS

### **Azure (Your Current - Deepen)**
```
AZURE DATA SERVICES
├── Azure Data Factory
│   ├── Pipelines, Activities
│   ├── Data flows
│   ├── Triggers
│   └── Integration runtime
│
├── Azure Databricks
│   ├── Workspace management
│   ├── Delta Lake
│   ├── Unity Catalog
│   ├── Jobs & Workflows
│   └── MLflow
│
├── Azure Synapse
│   ├── Dedicated SQL pools
│   ├── Serverless SQL
│   ├── Spark pools
│   └── Data Explorer
│
└── Storage
    ├── ADLS Gen2
    ├── Blob Storage
    └── Access patterns
```

### **AWS (Learn Basics)**
```
AWS DATA SERVICES
├── S3 (Storage)
├── Glue (ETL)
├── Athena (Query)
├── Redshift (Warehouse)
├── EMR (Spark)
├── Kinesis (Streaming)
└── Lambda (Serverless)
```

### **GCP (Awareness)**
```
GCP DATA SERVICES
├── BigQuery
├── Dataflow
├── Dataproc
├── Pub/Sub
└── Cloud Storage
```

---

## 🔟 DEVOPS & TOOLS

### **Topics to Master**

```
VERSION CONTROL
├── Git fundamentals
├── Branching strategies
├── Pull requests
├── Code review
└── Git workflows

CONTAINERIZATION
├── Docker
│   ├── Dockerfile
│   ├── Images & Containers
│   ├── Docker Compose
│   └── Best practices
│
└── Kubernetes (basics)
    ├── Pods, Services
    ├── Deployments
    └── ConfigMaps, Secrets

INFRASTRUCTURE AS CODE
├── Terraform
│   ├── Resources
│   ├── Variables
│   ├── Modules
│   └── State management
│
└── Cloud-specific (ARM, CloudFormation)

CI/CD
├── GitHub Actions
├── Azure DevOps
└── Pipeline patterns
```

---

## 1️⃣1️⃣ SOFT SKILLS

### **Communication**
```
TECHNICAL COMMUNICATION
├── Explaining complex concepts simply
├── Whiteboard/diagramming
├── Technical writing
├── Documentation
└── Presenting to stakeholders

INTERVIEW COMMUNICATION
├── Think out loud
├── Ask clarifying questions
├── Structure your approach
├── Handle hints gracefully
└── Admit knowledge gaps appropriately
```

### **Behavioral Skills**
```
LEADERSHIP PRINCIPLES
├── Ownership
├── Bias for action
├── Earn trust
├── Dive deep
├── Deliver results
└── Learn and be curious

STAR METHOD
├── Situation
├── Task
├── Action
├── Result
└── Learnings
```

---

## 📅 Skills Learning Timeline

```
MONTH 1-2:   DSA Foundations + SQL Advanced + Python Intermediate
MONTH 3-4:   DSA Core + Spark Deep Dive + Kafka Basics
MONTH 5-6:   DSA Advanced + System Design Fundamentals + Airflow
MONTH 7-8:   DSA Interview Level + System Design Practice + dbt
MONTH 9-10:  Mock Interviews + Cloud Expansion + Projects
MONTH 11:    Company-Specific Prep + Final Polish
```

---

## ✅ Skills Checklist (Print This!)

### **Must Have (Interview Blockers)**
- [ ] DSA: 300+ problems, Medium in 25 min
- [ ] SQL: Window functions, CTEs, optimization
- [ ] Python: Production-grade, testing, OOP
- [ ] Spark: Internals, tuning, can optimize any job
- [ ] System Design: 10+ designs practiced
- [ ] Behavioral: 15+ STAR stories ready

### **Should Have (Differentiators)**
- [ ] Kafka: Architecture, producers/consumers
- [ ] Airflow: DAG development, best practices
- [ ] Data Modeling: Kimball, SCD types
- [ ] Cloud: Multi-cloud awareness
- [ ] dbt: Transformations, testing

### **Nice to Have (Bonus Points)**
- [ ] Docker/K8s basics
- [ ] Terraform basics
- [ ] Data quality frameworks
- [ ] MLOps awareness

---

Would you like me to create a **detailed learning plan with specific resources** for any of these skills? Or shall I create a **week-by-week study schedule** combining all these skills?
