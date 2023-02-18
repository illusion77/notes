# Why
- Users consume more content than they creat
- The read operations fetch data from different sources (MySQL, HDFS and backend services)

# Pros
- A simple set of operations (set, get and delete)

# Cons

# Both
- separating a single cache layer

# How


# Delete or Update?
- They are idempotent. The common practice is to delete, but if latency > consistency, then update > delete, visce versa

# Scenario
## Generic cache
- use memcache to store pre-computed results from sophisticated machine learning algorithm


