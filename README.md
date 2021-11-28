
System Design Learnings
=======================
Daily Learnings from Books and Blogs related System Design
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Research Papers](#research-papers)
    - [Papers we love](#papers-we-love)
- [DB & Storage Engines](#db--storage-engines)
    - [MyRocks: A space- and write-optimized MySQL database](#myrocks-a-space--and-write-optimized-mysql-database)
    - [zippydb](#zippydb)
- [AWS](#aws)
    - [This is My Architecture video series](#this-is-my-architecture-video-series)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Research Papers
#### [Papers we love](https://github.com/papers-we-love/papers-we-love)

## Fundamentals of Distributed System
[Fundamental of Distributed System](https://www.baeldung.com/cs/distributed-systems-guide) article gives
* Basic definition of what is Distributed System and Decentralized System. 
* Gives general framework of what to focus on when discussing about distributed system i.e. 
    * Does the system follow primary-secondary or peer-peer architecture ? 
    * How does data gets partitioned ? 
    * How does nodes co-ordinate ? 
* Overview of System explained over above framework
    * Cassandra
    * Mongodb
    * Redis
    * Kafka 
* Important concepts
    * Consistent Hashing for data partitioning 
    * Gossip protocol for concensus/co-ordination of nodes 
    
## DB & Storage Engines
#### [MyRocks: A space- and write-optimized MySQL database](https://engineering.fb.com/2016/08/31/core-data/myrocks-a-space-and-write-optimized-mysql-database/)
  * InnoDB: 
    * Pros: 
      - great performance and reliability for a variety of workload
    * Cons: 
      - space and [write amplification](https://www.ontrack.com/en-us/blog/what-is-write-amplification-wa-and-how-does-it-effect-ssds) when used with flash storage
#### [zippydb](https://engineering.fb.com/2021/08/06/core-data/zippydb/)
## AWS
#### [This is My Architecture video series](https://go.aws/3lcQkTm)
- Pretty good video series on how Amazon customers use AWS products for their problem.  
  
   

