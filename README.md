
System Design Learnings
=======================

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [System Design Learnings](#system-design-learnings)
- [DB & Storage Engines](#db--storage-engines)
  - [MyRocks: A space- and write-optimized MySQL database](#myrocks-a-space--and-write-optimized-mysql-database)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->


# DB & Storage Engines
## [MyRocks: A space- and write-optimized MySQL database](https://engineering.fb.com/2016/08/31/core-data/myrocks-a-space-and-write-optimized-mysql-database/) 
 - InnoDB: 
   - Pros: 
     - great performance and reliability for a variety of workload
   - Cons: 
     - space and [write amplification](https://www.ontrack.com/en-us/blog/what-is-write-amplification-wa-and-how-does-it-effect-ssds) when used with flash storage
  
   

