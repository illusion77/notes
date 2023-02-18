# SDI Tips
- two co-workers collaborate on an ambiguous problem
- no perfect answer, focus on the process
- clarification, draw, do some scale assumption (use given use cases)
- wrap up

# Database
- relational or non-relational database
- non-relational: super-low latency (high performance), unstructured data, serialize and deserialize data, massive amount of data, scalability (horizontally scalable)

# Vertical scaling vs horizontal scaling
vertical: add CPU and RAM
horizontal: add machine
vertical scaling is simple but has some limitations, like a single point of failure
- Resharding data (shard exhaustion)
- Celebrity problem (hotspot key problem)
- Join and de-normalization

# Load balancer
solve high traffic volume
- Pros: traffic management
- Cons: SPOF, (cost, configuration complexity, security)

# Database replication
solve failover and redundancy
- Pros: high availability, scalability, performance
- Cons: sync, (cost, complexity, security)

# Cache
Scenario: read-frequently but modified infrequently
- Expiration policy
- Eviction Policy: LRU, LFU, FIFO
- Consistency
	- [[Scaling Memcache at Facebook]]
- Mitigating failures: SPOF

# CDN
caching static content
- Pros: reduced server load, improved security, availability, performance
- Cons: potential for caching issues, (cost, configuration complexity)

# Stateful & Stateless architecture

# Data centers
Traffic redirection, Data synchronization ([Netflix](https://netflixtechblog.com/active-active-for-multi-regional-resiliency-c47719f6685b)), Test and deployment

# Message queue

# Logging, metrics, automation

