# Backend Architect Technical Map

[![Knowledge Sharing Agreement (CC Agreement)](https://camo.githubusercontent.com/95c3d7ef0b5da8445087e462514063675f79321d/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6963656e73652d4372656174697665253230436f6d6d6f6e732d4443334432342e737667)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh) [![GitHub stars](https://camo.githubusercontent.com/763dd2a5655865531ab8c1362fbae75a14ae7630/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f78696e677368616f6368656e672f6172636869746563742d617765736f6d652e7376673f7374796c653d666c6174266c6162656c3d53746172)](https://github.com/xingshaocheng/architect-awesome/stargazers) [![GitHub forks](https://camo.githubusercontent.com/026e492b9b2115029f2a1cc3dd6e70b60e19b1e3/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f666f726b732f78696e677368616f6368656e672f6172636869746563742d617765736f6d652e7376673f7374796c653d666c6174266c6162656c3d466f726b)](https://github.com/xingshaocheng/architect-awesome/fork) [![GitHub watchers](https://camo.githubusercontent.com/6142770bd3ad9f0ab17d68a33bf1ed2454691181/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f77617463686572732f78696e677368616f6368656e672f6172636869746563742d617765736f6d652e7376673f7374796c653d666c6174266c6162656c3d5761746368)](https://github.com/xingshaocheng/architect-awesome/watchers)

**Last updated on 20180502**
* [data structure](#data-structure)
	* [queue](#queue)
	* [set](#set)
	* [Lists, arrays](#lists-arrays)
	* [Dictionary, associative array](#dictionary-associative-array)
	* [Stack](#stack)
	* [tree](#tree)
		* [Binary tree](#binary-tree)
		* [Complete Binary Tree](#complete-binary-tree)
		* [Balanced binary tree](#balanced-binary-tree)
		* []()
		* [Red black tree](#red-black-tree)
		* [B-, B+, B* trees](#b--b-b-trees)
		* [LSM tree](#lsm-tree)
	* [BitSet](#bitset)
* [Common algorithms](#common-algorithms)
	* [Sorting, finding algorithm](#sorting-finding-algorithm)
		* [Select sort](#select-sort)
		* [Bubble Sort](#bubble-sort)
		* [Insert sort](#insert-sort)
		* [Quick sort](#quick-sort)
		* [Merge sort](#merge-sort)
		* [Hill Sort](#hill-sort)
		* [Heap sort](#heap-sort)
		* [Counting sort](#counting-sort)
		* [Bucket sort](#bucket-sort)
		* [Cardinal sort](#cardinal-sort)
		* [Binary search](#binary-search)
		* [Sorting tools in Java](#sorting-tools-in-java)
	* [Bloom filter](#bloom-filter)
	* [String comparison](#string-comparison)
		* [KMP algorithm](#kmp-algorithm)
	* [Depth first, breadth first](#depth-first-breadth-first)
	* [how are you](#how-are-you)
	* [Backtracking algorithm](#backtracking-algorithm)
	* [Pruning algorithm](#pruning-algorithm)
	* [Dynamic planning](#dynamic-planning)
	* [Naive Bayes](#naive-bayes)
	* [Recommended algorithm](#recommended-algorithm)
	* [Minimum spanning tree algorithm](#minimum-spanning-tree-algorithm)
	* [Shortest path algorithm](#shortest-path-algorithm)
* [Concurrent](#concurrent)
	* [Multithreading](#multithreading)
	* [Thread safety](#thread-safety)
	* [Consistency, transaction](#consistency-transaction)
		* [Transaction ACID features](#transaction-acid-features)
		* [Transaction isolation level](#transaction-isolation-level)
		* [MVCC](#mvcc)
	* [lock](#lock)
		* [Locks and synchronization classes in Java](#locks-and-synchronization-classes-in-java)
		* [Fair lock &amp; non-fair lock](#fair-lock--non-fair-lock)
		* [Pessimistic lock](#pessimistic-lock)
		* [Optimistic Lock &amp; CAS](#optimistic-lock--cas)
		* [ABA issues](#aba-issues)
		* [CopyOnWrite container](#copyonwrite-container)
		* [RingBuffer](#ringbuffer)
		* [Reentrant Locks &amp; Non-Reentrant Locks](#reentrant-locks--non-reentrant-locks)
		* [Mutexes &amp; shared locks](#mutexes--shared-locks)
		* [Deadlock](#deadlock)
* [operating system](#operating-system)
	* [Principle of computer](#principle-of-computer)
	* [CPU](#cpu)
		* [Multi-level cache](#multi-level-cache)
	* [process](#process)
	* [Threads](#threads)
	* [Correspondence](#correspondence)
	* [Linux](#linux)
* [Design Patterns](#design-patterns)
	* [Six principles of design patterns](#six-principles-of-design-patterns)
	* [23 common design patterns](#23-common-design-patterns)
	* [Application scenario](#application-scenario)
	* [Singleton mode](#singleton-mode)
	* [Chain of responsibility model](#chain-of-responsibility-model)
	* [MVC](#mvc)
	* [IOC](#ioc)
	* [AOP](#aop)
	* [UML](#uml)
	* [Microservice idea](#microservice-idea)
		* [Conway Law](#conway-law)
* [Operation &amp; Statistics &amp; Technical Support](#operation--statistics--technical-support)
	* [General monitoring](#general-monitoring)
	* [APM](#apm)
	* [Statistical Analysis](#statistical-analysis)
	* []()
		* [Jenkins](#jenkins)
		* [Environmental separation](#environmental-separation)
	* [Automation operation and maintenance](#automation-operation-and-maintenance)
		* [Ansible](#ansible)
		* [Puppet](#puppet)
		* [Chef](#chef)
	* [test](#test)
		* [TDD theory](#tdd-theory)
		* [unit test](#unit-test)
		* [pressure test](#pressure-test)
		* [Full-link pressure test](#full-link-pressure-test)
		* [A/B, grayscale, blue-green test](#ab-grayscale-blue-green-test)
	* [Virtualization](#virtualization)
		* [KVM](#kvm)
		* [Xen](#xen)
		* [OpenVZ](#openvz)
	* [Container technology](#container-technology)
		* [Docker](#docker)
	* [Cloud technology](#cloud-technology)
		* [OpenStack](#openstack)
	* [DevOps](#devops)
	* [Document management](#document-management)
* [Middleware](#middleware)
	* [Web Server](#web-server)
		* [Nginx](#nginx)
		* [OpenResty](#openresty)
		* [Apache Httpd](#apache-httpd)
		* [Tomcat](#tomcat)
			* [Architecture principle](#architecture-principle)
			* [Tuning plan](#tuning-plan)
		* [Jetty](#jetty)
	* [Caching](#caching)
		* [Local cache](#local-cache)
	* [Client Cache](#client-cache)
	* [Server cache](#server-cache)
		* [Web Cache](#web-cache)
		* [Memcached](#memcached)
		* [Redis](#redis)
			* [Structure](#structure)
			* [Recovery strategy](#recovery-strategy)
		* [Tair](#tair)
	* [message queue](#message-queue)
		* [Message bus](#message-bus)
		* [Order of messages](#order-of-messages)
		* [RabbitMQ](#rabbitmq)
		* [RocketMQ](#rocketmq)
		* [ActiveMQ](#activemq)
		* [Kafka](#kafka)
		* [Redis message push](#redis-message-push)
		* [ZeroMQ](#zeromq)
	* [Scheduled scheduling](#scheduled-scheduling)
		* [Stand-alone scheduled scheduling](#stand-alone-scheduled-scheduling)
		* [Distributed timing scheduling](#distributed-timing-scheduling)
	* [RPC](#rpc)
		* [Dubbo](#dubbo)
		* [Thrift](#thrift)
		* [gRPC](#grpc)
	* [Database middleware](#database-middleware)
		* [Sharding Jdbc](#sharding-jdbc)
	* [Log system](#log-system)
		* [Log collection](#log-collection)
	* [Configuration Center](#configuration-center)
	* [API Gateway](#api-gateway)
* [The internet](#the-internet)
	* [protocol](#protocol)
		* [OSI Layer 7 Protocol](#osi-layer-7-protocol)
		* [TCP/IP](#tcpip)
		* [HTTP](#http)
		* [HTTP2.0](#http20)
		* [HTTPS](#https)
	* [Network model](#network-model)
		* [Epoll](#epoll)
		* [Java NIO](#java-nio)
		* [Kqueue](#kqueue)
	* [Connections and short connections](#connections-and-short-connections)
	* [frame](#frame)
	* [Zero-copy](#zero-copy)
	* []()
		* [Hessian](#hessian)
		* [Protobuf](#protobuf)
* [database](#database)
	* [Basic theory](#basic-theory)
		* [Three paradigms of database design](#three-paradigms-of-database-design)
	* [MySQL](#mysql)
		* [principle](#principle)
		* [InnoDB](#innodb)
		* [optimization](#optimization)
		* [index](#index)
			* [Clustered index, non-clustered index](#clustered-index-non-clustered-index)
			* [Composite index](#composite-index)
			* []()
		* [Explain](#explain)
	* [NoSQL](#nosql)
		* [MongoDB](#mongodb)
		* [Hbase](#hbase)
* [search engine](#search-engine)
	* [Search Engine Principle](#search-engine-principle)
	* [Lucene](#lucene)
	* [Elasticsearch](#elasticsearch)
	* [Solr](#solr)
	* [Sphinx](#sphinx)
* [performance](#performance)
	* [Performance Optimization Methodology](#performance-optimization-methodology)
	* [Capacity assessment](#capacity-assessment)
	* [CDN network](#cdn-network)
	* [connection pool](#connection-pool)
	* [Performance tuning](#performance-tuning)
* [Big Data](#big-data)
	* [Flow calculation](#flow-calculation)
		* [Storm](#storm)
		* [Flink](#flink)
		* [Kafka Stream](#kafka-stream)
		* [Application scenario](#application-scenario-1)
	* [Hadoop](#hadoop)
		* [HDFS](#hdfs)
		* [MapReduce](#mapreduce)
		* [Yarn](#yarn)
	* [Spark](#spark)
* [Safety](#safety)
	* [Web security](#web-security)
		* [XSS](#xss)
		* [CSRF](#csrf)
		* [SQL injection](#sql-injection)
		* [Hash Dos](#hash-dos)
		* [Script injection](#script-injection)
		* [Vulnerability Scan Tool](#vulnerability-scan-tool)
		* [Verification code](#verification-code)
	* [DDoS protection](#ddos-protection)
	* [User privacy protection](#user-privacy-protection)
	* [Serialization vulnerability](#serialization-vulnerability)
	* [encrypt and decode](#encrypt-and-decode)
		* [Symmetric encryption](#symmetric-encryption)
		* [Hash algorithm](#hash-algorithm)
		* [Asymmetric encryption](#asymmetric-encryption)
	* [Server security](#server-security)
	* [Data Security](#data-security)
		* [data backup](#data-backup)
	* [Network isolation](#network-isolation)
		* [Internal and external network separation](#internal-and-external-network-separation)
		* [Login board](#login-board)
	* [Authorization, certification](#authorization-certification)
		* [RBAC](#rbac)
		* [OAuth2.0](#oauth20)
		* []()
		* []()
* [Common open source framework](#common-open-source-framework)
	* [Open Source Agreement](#open-source-agreement)
	* [Logging framework](#logging-framework)
		* [Log4j, Log4j2](#log4j-log4j2)
		* [Logback](#logback)
	* [ORM](#orm)
	* [Network framework](#network-framework)
	* [Web framework](#web-framework)
		* [Spring family](#spring-family)
	* [Tool frame](#tool-frame)
* [Distributed design](#distributed-design)
	* [Scalable design](#scalable-design)
	* [Stability &amp; High Availability](#stability--high-availability)
		* [Hardware load balancing](#hardware-load-balancing)
		* [Software load balancing](#software-load-balancing)
		* [Limiting](#limiting)
		* [Application layer disaster recovery](#application-layer-disaster-recovery)
		* [Cross-room disaster recovery](#cross-room-disaster-recovery)
		* [Disaster recovery drill process](#disaster-recovery-drill-process)
		* [Smooth start](#smooth-start)
	* [Database expansion](#database-expansion)
		* [Read-write separation mode](#read-write-separation-mode)
		* [Fragmentation mode](#fragmentation-mode)
	* [Service governance](#service-governance)
		* [Service Registration and Discovery](#service-registration-and-discovery)
		* [Service Routing Control](#service-routing-control)
	* [Distributed consensus](#distributed-consensus)
		* [CAP and BASE theory](#cap-and-base-theory)
		* [Distributed lock](#distributed-lock)
		* [Distributed consensus algorithm](#distributed-consensus-algorithm)
			* [PAXOS](#paxos)
			* [Zab](#zab)
			* [Raft](#raft)
			* [Gossip](#gossip)
			* [Two-phase commit, multi-phase commit](#two-phase-commit-multi-phase-commit)
		* [Idempotent](#idempotent)
		* [Distributed consensus solution](#distributed-consensus-solution)
		* [Distributed Leader node election](#distributed-leader-node-election)
		* [Flexible Transactions](#flexible-transactions)
	* [Distributed File System](#distributed-file-system)
	* [Unique ID generation](#unique-id-generation)
		* [Globally unique ID](#globally-unique-id)
	* [Consistent hashing algorithm](#consistent-hashing-algorithm)
* [Design Ideas &amp; Development Models](#design-ideas--development-models)
	* []()
		* []()
		* [Anemia, congestive model](#anemia-congestive-model)
	* [Actor mode](#actor-mode)
	* [Reactive programming](#reactive-programming)
		* [Reactor](#reactor)
		* [RxJava](#rxjava)
		* [Vert.x](#vertx)
	* [DODAF2.0](#dodaf20)
	* [Serverless](#serverless)
	* [Service Mesh](#service-mesh)
* [Project management](#project-management)
	* [Architecture review](#architecture-review)
	* [Reconstruction](#reconstruction)
	* [Code specification](#code-specification)
	* [Code Review](#code-review)
	* [RUP](#rup)
	* [Kanban Management](#kanban-management)
	* [SCRUM](#scrum)
	* [Agile development](#agile-development)
	* []()
	* [Pair programming](#pair-programming)
	* [FMEA management model](#fmea-management-model)
* [General Business Terms](#general-business-terms)
* [Technical trends](#technical-trends)
* [Policies and regulations](#policies-and-regulations)
	* [legal](#legal)
		* [Strictly abide by Article 253 of the Criminal Law](#strictly-abide-by-article-253-of-the-criminal-law)
* [Architect quality](#architect-quality)
* [Team management](#team-management)
	* [Recruitment](#recruitment)
* [Information](#information)
	* [Industry information](#industry-information)
	* [Public number list](#public-number-list)
	* [Blog](#blog)
		* [Team blog](#team-blog)
		* [personal blog](#personal-blog)
	* [Integrated portal, community](#integrated-portal-community)
	* [Q&amp;A, discussion community](#qa-discussion-community)
	* [Industry data analysis](#industry-data-analysis)
	* [Special website](#special-website)
	* [other](#other)
	* [Recommended reference book](#recommended-reference-book)
		* [Online eBooks](#online-ebooks)
		* [Paper book](#paper-book)
			* [Development aspects](#development-aspects)
			* [Architecture aspects](#architecture-aspects)
			* [Technical management](#technical-management)
			* [Basic theory](#basic-theory-1)
			* [Tools](#tools)
			* [Big data](#big-data-1)
* [Technical resources](#technical-resources)
	* [Open source resources](#open-source-resources)
	* [Manuals, Documents, Tutorials](#manuals-documents-tutorials)
	* [Online class](#online-class)
	* [conference](#conference)
	* [Common APP](#common-app)
	* [find a job](#find-a-job)
	* [tool](#tool)
	* [Code hosting](#code-hosting)
	* [File service](#file-service)
	* [Comprehensive cloud service provider](#comprehensive-cloud-service-provider)
		* [VPS](#vps)

**(Toc generated by</font> </font>[simple-php-github-toc](https://github.com/xingshaocheng/simple-php-github-toc)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">)**

# data structure

## queue

*   ["java queue - detailed analysis of queue"](https://www.cnblogs.com/lemon-flm/p/7877898.html)

    *   Non-blocking queue: ConcurrentLinkedQueue (unbounded thread safe), using CAS mechanism (compareAndSwapObject atomic operation).
    *   Blocking queues: ArrayBlockingQueue (bounded), LinkedBlockingQueue (unbounded), DelayQueue, PriorityBlockingQueue, using lock mechanism; use ReentrantLock lock.
*   ["LinkedList, ConcurrentLinkedQueue, LinkedBlockingQueue Comparative Analysis"](https://www.cnblogs.com/mantu/p/5802393.html)

## set

*   ["Details of Java Set Collection"](https://blog.csdn.net/qq_33642117/article/details/52040345)

## Lists, arrays

*   ["Java Collection Detailed - What is a List"](https://blog.csdn.net/wz249863091/article/details/52853360)

## Dictionary, associative array

*   ["Java map details - usage, traversal, sorting, common APIs, etc."](https://baike.xsoftlab.net/view/250.html)

## Stack

*   ["Stack design and implementation of java data structure and algorithm"](https://blog.csdn.net/javazejian/article/details/53362993)
*   [Java Stack Class](http://www.runoob.com/java/java-stack-class.html)
*   ["Detailed Implementation Analysis of Java Stack"](https://blog.csdn.net/f2006116/article/details/51375225)
    *   Stack is thread-safe.
    *   Internal use array to save data, double when not enough.

## tree

### Binary tree

Each node has a maximum of two leaf nodes.

*   [Binary Tree](https://blog.csdn.net/cai2016/article/details/52589952)

### Complete Binary Tree

*   [Complete Binary Tree](https://baike.baidu.com/item/%E5%AE%8C%E5%85%A8%E4%BA%8C%E5%8F%89%E6%A0%91/7773232?fr=aladdin)
    *   The leaf nodes can only appear at the bottom and sub-lower levels, and the nodes at the bottom level are all concentrating on the binary tree at the leftmost position of the layer.

### Balanced binary tree

The absolute value of the height difference between the left and right two subtrees does not exceed one, and both the left and right subtrees are balanced binary trees.

*   ["On Data Structure - Balanced Binary Tree"](http://www.cnblogs.com/polly333/p/4798944.html)
*   ["On the algorithm and data structure: eight balanced tree search 2-3 tree"](http://www.cnblogs.com/yangecnu/p/Introduce-2-3-Search-Tree.html)

### 

Binary Search Trees, also called ordered binary trees, are sorted binary trees.

*   ["On the algorithm and data structure: seven binary search tree"](http://www.cnblogs.com/yangecnu/p/Introduce-Binary-Search-Tree.html)

### Red black tree

*   ["Easiest to understand red and black trees"](https://blog.csdn.net/sun_tttt/article/details/65445754)
    *   After the addition phase, left-handed or right-handed to reach equilibrium again.
*   ["On Algorithms and Data Structures: Nine Balanced Search Trees for Red and Black Trees"](http://www.cnblogs.com/yangecnu/p/Introduce-Red-Black-Tree.html)

### B-, B+, B* trees

MySQL is based on the B+ tree clustered index organization table

*   ["B-tree, B+ tree, B* tree"](https://blog.csdn.net/aqzwss/article/details/53074186)
*   ["Comparison of the advantages and disadvantages of B-trees, B+ trees and B* trees"](https://blog.csdn.net/bigtree_3721/article/details/73632405)
    *   The tree structure of the leaf nodes of the B+ tree is more convenient than the B-tree for scanning and range retrieval.

### LSM tree

Compared with B+ trees, LSM (Log-Structured Merge-Trees) sacrifices partial read performance in exchange for write performance (through batch writes) and achieves read and write.</font> <font style="vertical-align: inherit;">Hbase, LevelDB, Tair (Long DB), and nessDB use the structure of the LSM tree.</font> <font style="vertical-align: inherit;">LSM can quickly establish an index.

*   [LSM Tree vs B+ Tree](https://blog.csdn.net/dbanote/article/details/8897599)

    *   The B+ tree read performance is good, but due to the need for an orderly structure, the disk seeks frequently when the keys are scattered, resulting in write performance.
    *   LSM divides a large tree into N small trees, first writes to memory (without seeking problems, high performance), and builds an ordered small tree (ordered tree) in memory. The bigger the memory tree is flushed to disk.</font> <font style="vertical-align: inherit;">When reading, because it does not know which tree the data is on, it is necessary to traverse (bi-search) all the small trees, but the data is ordered inside each small tree.
*   [LSM Tree (Log-Structured Merge Tree Storage Engine)](https://blog.csdn.net/u014774781/article/details/52105708)

    *   In extreme terms, the write performance of HBase based on the LSM tree is an order of magnitude higher than that of MySQL, and the read performance is an order of magnitude lower.
    *   Optimization method: Bloom filter replaces binary search; compact decimal tree, improves query performance.
    *   In Hbase, when the memory reaches a certain threshold, the entire flush flushes to disk and forms a file (B+ number). HDFS does not support the update operation. Therefore, Hbase does an overall flush instead of a merge update.</font> <font style="vertical-align: inherit;">Flush to the small tree on the disk, periodically merged into a big tree.

## BitSet

It is often used for checking the weight of large-scale data.

*   ["Java Bitset Class"](http://www.runoob.com/java/java-bitset-class.html)
*   [Java BitSet (bit set)](https://blog.csdn.net/caiandyong/article/details/51581160)

# Common algorithms

*   ["Common sorting algorithms and their corresponding time complexity and space complexity"](https://blog.csdn.net/gane_cheng/article/details/52652705)

## Sorting, finding algorithm

*   ["Common sorting algorithms and their corresponding time complexity and space complexity"](https://blog.csdn.net/gane_cheng/article/details/52652705)

### Select sort

*   ["Selection Sort of Classic Algorithms in Java"](https://www.cnblogs.com/shen-hua/p/5424059.html)
    *   Each tick selects the smallest element from the records to be sorted, and the order is placed at the end of the sorted sequence until all records are sorted.

### Bubble Sort

*   ["Two kinds of writing bubble sorting"](https://blog.csdn.net/shuaizai88/article/details/73250615)
    *   Exchange adjacent elements before and after, the largest row to the end.
    *   Time complexity O(n2)

### Insert sort

*   ["Sorting algorithm summary insertion sort"](https://www.cnblogs.com/hapjin/p/5517667.html)

### Quick sort

*   [Sitting on the toilet looking algorithm: quick sort](http://developer.51cto.com/art/201403/430986.htm)
    *   One side is larger or smaller than the other.

### Merge sort

*   ["Image Sorting Algorithm (4) Merge and Sorting"](http://www.cnblogs.com/chengxiao/p/6194356.html)
    *   Divide and conquer, sort into small parts and merge (recreate a new space for copying).

### Hill Sort

TODO

### Heap sort

*   ["Graphical sorting algorithm (three) of the heap sort"](https://www.cnblogs.com/chengxiao/p/6129630.html)
    *   The sorting process is the process of building a maximum heap. The maximum heap: The value of each node is greater than or equal to the value of its child nodes, and the top element is the maximum value.

### Counting sort

*   [Counting and Bucket Sorting](https://www.cnblogs.com/suvllian/p/5495780.html)
    *   Compared to the bucket sorting process, the difference lies in the number of buckets.

### Bucket sort

*   ["[Aha!</font> <font style="vertical-align: inherit;">Algorithms] The Fastest and Simplest Sorting - Bucket Sorting](http://blog.51cto.com/ahalei/1362789)
*   ["Sort Algorithm (3): Counting and Bucket Sorting"](https://blog.csdn.net/sunjinshengli/article/details/70738527)
    *   Bucket sorting divides the [0,1) interval into n sub-intervals of the same size, which are called buckets.
    *   Each bucket is sorted individually and then it traverses each bucket.

### Cardinal sort

Sort by rank, ten, hundred, ...

*   [Sort Algorithm Series: Cardinal Sorting](https://blog.csdn.net/lemon_tree12138/article/details/51695211)
*   [Cardinal Sort](https://www.cnblogs.com/skywang12345/p/3603669.html)

### Binary search

*   ["Two-point search (java implementation)"](https://www.cnblogs.com/coderising/p/5708632.html)

    *   The sequence to be searched is ordered.
    *   Time complexity O(logN).
*   ["java realize binary search - two ways"](https://blog.csdn.net/maoyuanming0806/article/details/78176957)

    *   While + recursively.

### Sorting tools in Java

*   [Analysis of Arrays.sort and Collections.sort Implementation Principles](https://blog.csdn.net/u011410529/article/details/56668545?locationnum=6&fps=1)
    *   The Collections.sort algorithm calls the merge sort.
    *   Arrays.sort() uses two sorting algorithms -- basic sort data using quick sorting, and object arrays using merge sorting.

## Bloom filter

Commonly used for big data, such as email, url, etc.</font> <font style="vertical-align: inherit;">Core principle: Generate a fingerprint (a byte or bytes, but certainly a lot less than the original data) by calculating each piece of data, each of which is obtained by random calculation, mapping the fingerprint to a large The bitwise storage space.</font> <font style="vertical-align: inherit;">Note: There will be a certain error rate.</font> <font style="vertical-align: inherit;">Advantages: High space and time efficiency.</font> <font style="vertical-align: inherit;">Disadvantages: As the number of deposited elements increases, the miscalculation rate increases.

*   [Bloom Filter - Spatially Efficient Data Structure](https://segmentfault.com/a/1190000002729689)
*   ["Large Data Deduplication: Bitmap and Bloom Filters"](https://blog.csdn.net/zdxiq000/article/details/57626464)
*   ["The Implementation of Bloom Filter Based on Redis"](https://blog.csdn.net/qq_30242609/article/details/71024458)
    *   Redis-based Bitmap data structure.
*   ["Web crawler: Use of Bloom filter for URL deduplication policy"](https://blog.csdn.net/lemon_tree12138/article/details/47973715)
    *   Use the BitSet class and weighted hashing algorithm in Java.

## String comparison

### KMP algorithm

KMP: The core principle of the Knuth-Morris-Pratt algorithm (abbreviated as KMP) is to use a "partial match table" to skip over elements that have already been matched.

*   [String Matching KMP Algorithm](http://www.ruanyifeng.com/blog/2013/05/Knuth%E2%80%93Morris%E2%80%93Pratt_algorithm.html)

## Depth first, breadth first

*   [Breadth First Search BFS and Depth First Search DFS](https://www.cnblogs.com/0kk470/p/7555033.html)

## how are you

*   ["Algorithm: Fundamentals of Greedy Algorithm"](https://www.cnblogs.com/MrSaver/p/8641971.html)
*   ["Common Algorithms and Problem Scenarios - Greedy Algorithm"](https://blog.csdn.net/a345017062/article/details/52443781)

## Backtracking algorithm

*   ["Five commonly used algorithms: Backtracking method"](https://blog.csdn.net/qfikh/article/details/51960331)

## Pruning algorithm

*   ["α-β Pruning Algorithm"](https://blog.csdn.net/luningcsdn/article/details/50930276)

## Dynamic planning

*   ["Detailed Explanation of Dynamic Planning - Zou Bo Talks about Dynamic Planning"](https://www.cnblogs.com/little-YTMM/p/5372680.html)
*   ["Personal Understanding of Dynamic Programming Algorithms"](https://blog.csdn.net/yao_zi_jie/article/details/54580283)

## Naive Bayes

*   ["Take You Through the Naive Bayes Classification Algorithm"](https://blog.csdn.net/amds123/article/details/70173402)

    *   P(B|A)=P(A|B)P(B)/P(A)
*   [Bayesian Inference and Internet Applications 1](http://www.ruanyifeng.com/blog/2011/08/bayesian_inference_part_one.html)

*   [Bayesian Inference and Internet Applications 2](http://www.ruanyifeng.com/blog/2011/08/bayesian_inference_part_two.html)

## Recommended algorithm

*   ["Recommendation algorithm review"](http://www.infoq.com/cn/articles/recommendation-algorithm-overview-part01)
*   ["Introduction to TOP 10 Open Source Recommendation System"](https://www.oschina.net/news/51297/top-10-open-source-recommendation-systems)

## Minimum spanning tree algorithm

*   ["Introduction to Algorithms - Minimum Spanning Tree (Kruskal and Prim Algorithms)"](https://blog.csdn.net/luoshixian099/article/details/51908175)

## Shortest path algorithm

*   ["Dijkstra Algorithm Detailed"](https://blog.csdn.net/qq_35644234/article/details/60870719)

# Concurrent

1.  **Basic knowledge**

    1.1</font> </font>[advantages and disadvantages of concurrent programming](https://juejin.im/post/5ae6c3ef6fb9a07ab508ac85)

    Knowledge points: (1) Why use concurrency?</font> <font style="vertical-align: inherit;">(Advantages); (2) Disadvantages of concurrent programming; (3) Confusing concept

    1.2</font> </font>[Thread Status and Basic Operations](https://juejin.im/post/5ae6cf7a518825670960fcc2)

    Knowledge points: (1) how to create new threads; (2) thread state transitions; (3) basic thread operations; (4) daemon threads;

2.  **Concurrency Theory (JMM)**

    [Java memory model and happens-before rules](https://juejin.im/post/5ae6d309518825673123fd0e)

    Knowledge points: (1) JMM memory structure; (2) reordering; (3) happens-before rules

3.  **Concurrent Keyword**

    3.1</font> </font>[Let you thoroughly understand Synchronized](https://juejin.im/post/5ae6dc04f265da0ba351d3ff)

    Knowledge points: (1) how to use synchronized; (2) monitor mechanism; (3) synchronized happens-before relationship; (4) synchronized memory semantics; (5) lock optimization; (6) lock escalation strategy

    3.2</font> </font>[Let you thoroughly understand volatile](https://juejin.im/post/5ae9b41b518825670b33e6c4)

    Knowledge points: (1) implementation principle; (2) derivation of happens-before relations; (3) memory semantics; (4) realization of memory semantics

    3.3</font> </font>[Do you think you really understand final?](https://juejin.im/post/5ae9b82c6fb9a07ac3634941)

    Knowledge points: (1) how to use; (2) final reordering rules; (3) final implementation principles; (4) final references cannot "overflow" (this escape) from constructors

    3.4</font> </font>[Summary of the three major properties: atomicity, orderliness, visibility](https://juejin.im/post/5aeb022cf265da0b722af7b8)

    Knowledge points: (1) atomicity: synchronized; (2) visibility: synchronized, volatile; (3) orderliness: synchronized, volatile

4.  **Lock system**

    4.1</font> </font>[Meet Lock and AbstractQueuedSynchronizer (AQS)](https://juejin.im/post/5aeb055b6fb9a07abf725c8c)

    Knowledge points: (1) Lock and synchronized comparisons; (2) AQS design intent; (3) How to implement custom synchronization components using AQS; (4) Rewritable methods; (5) Template methods provided by AQS;

    4.2 In-</font> </font>[depth understanding of AbstractQueuedSynchronizer (AQS)](https://juejin.im/post/5aeb07ab6fb9a07ac36350c8)

    Knowledge points: (1) AQS synchronization queue data structure; (2) exclusive lock; (3) shared lock;

    4.3</font> </font>[Understanding ReentrantLock Again](https://juejin.im/post/5aeb0a8b518825673a2066f0)

    Knowledge points: (1) implementation principle of reentrant locks; (2) implementation principle of fair locks; (3) implementation principle of non-fair locks; (4) comparison of fair locks and non-fair locks

    4.4 In-</font> </font>[depth understanding of the read-write lock ReentrantReadWriteLock](https://juejin.im/post/5aeb0e016fb9a07ab7740d90)

    Knowledge points: (1) How to represent read/write status; (2) WriteLock acquisition and release; (3) ReadLock acquisition and release; (4) lock downgrading strategy; (5) Generation of Condition wait queues; (6) Application scenarios

    4.5</font> </font>[Detailed conditions await and signal wait / notification mechanism](https://juejin.im/post/5aeea5e951882506a36c67f0)

    Knowledge points: (1) Features that are comparable to the wait/notify mechanism of Object; (2) Methods corresponding to wait/notify of Object; (3) Underlying data structures; (4) Await implementation principles; (5) Signal/signalAll implementation principle; (6) combination of await and signal/signalAll;

    4.6</font> </font>[LockSupport Tool](https://juejin.im/post/5aeed27f51882567336aa0fa)

    Knowledge points: (1) main functions; (2) characteristics compared to synchronized blocking wake-up;

5.  **Concurrent container**

    5.1</font> </font>[concurrent containers ConcurrentHashMap (JDK 1.8 version)](https://juejin.im/post/5aeeaba8f265da0b9d781d16)

    Knowledge points: (1) key attributes; (2) important internal classes; (3) CAS operations involved; (4) construction methods; (5) put execution flow; (6) get execution flow; (7) expansion mechanism (8) Execution flow of method for counting size; (9) Comparison of ConcurrentHashMap version 1.8 with previous version

    5.2</font> </font>[CopyOnWriteArrayList of Concurrent Containers](https://juejin.im/post/5aeeb55f5188256715478c21)

    Knowledge points: (1) realization principle; (2) difference between COW and ReentrantReadWriteLock; (3) application scenario; (4) why there is weak consistency; (5) shortcomings of COW;

    5.3</font> </font>[ConcurrentLinkedQueue for Concurrent Containers](https://juejin.im/post/5aeeae756fb9a07ab11112af)

    Knowledge points: (1) implementation principle; (2) data structure; (3) core method; (4) design intent of delayed update of HOPS

    5.4</font> </font>[concurrent container ThreadLocal](https://juejin.im/post/5aeeb22e6fb9a07aa213404a)

    Knowledge points: (1) implementation principle; (2) set method principle; (3) get method principle; (4) remove method principle; (5) ThreadLocalMap

    [An article, from the source code in-depth detailed ThreadLocal memory leak problem](https://www.jianshu.com/p/dde92ec37bd1)

    Knowledge points: (1) ThreadLocal memory leak principle; (2) ThreadLocal best practices; (3) application scenarios

    5.5</font> </font>[Concurrent Container BlockingQueue](https://juejin.im/post/5aeebd02518825672f19c546)

    Knowledge points: (1) Basic operation of BlockingQueue; (2) Commonly used BlockingQueue;

    [Concurrent container ArrayBlockingQueue and LinkedBlockingQueue implementation principle explained](https://juejin.im/post/5aeebdb26fb9a07aa83ea17e)

6.  **Thread pool (Executor system)**

    6.1</font> </font>[Thread Pool Implementation Principle](https://juejin.im/post/5aeec0106fb9a07ab379574f)

    Knowledge points: (1) Why use a thread pool?</font> <font style="vertical-align: inherit;">(2) execution flow; (3) the meaning of each parameter of the constructor; (4) how to close the thread pool; (5) how to configure the thread pool;

    6.2</font> </font>[Thread Pool ScheduledThreadPoolExecutor](https://juejin.im/post/5aeec106518825670a10328a)

    Knowledge points: (1) class structure; (2) common methods; (3) ScheduledFutureTask; (3) DelayedWorkQueue;

    6.3</font> </font>[FutureTask Basic Operation Summary](https://juejin.im/post/5aeec249f265da0b886d5101)

    Knowledge points: (1) Several states of FutureTask; (2) get method; (3) cancel method; (4) application scenario; (5) implementation of Runnable interface

7.  **Atomic operations**

    7.1</font> </font>[Atomic Operation Classes in Atomic Packages in Java](https://juejin.im/post/5aeec351518825670a103292)

    Knowledge points: (1) implementation principle; (2) atomic update basic types; (3) atomic update array types; (4) atomic update reference types; (5) atomic update field types

8.  **Concurrency tools**

    8.1</font> </font>[Big vernacular Java Concurrency Tool - CountDownLatch, CyclicBarrier](https://juejin.im/post/5aeec3ebf265da0ba76fa327)

    Knowledge Points: (1) CountDownLatch, (2) CyclicBarrier, and (3) Comparison between CountDownLatch and CyclicBarrier

    8.2</font> </font>[Big vernacular Java Concurrency Tools - Semaphore, Exchanger](https://juejin.im/post/5aeec49b518825673614d183)

    Knowledge Points: (1) Resource Access Control Semaphore; (2) Data Exchange Exchanger

9.  **Concurrent practice**

    9.1</font> </font>[An article that lets you thoroughly understand the producer-consumer problem](https://juejin.im/post/5aeec675f265da0b7c072c56)

> JAVA concurrent knowledge map

**Move to a new window, zoom in to see better results or view originals**

[Knowledge map artwork link, if useful, can be cloned for use](https://www.processon.com/view/5ab5a979e4b0a248b0e026b3?fromnew=1)

[![JAVA concurrency knowledge map.png](https://github.com/CL0610/Java-concurrency/raw/master/Java%E5%B9%B6%E5%8F%91%E7%9F%A5%E8%AF%86%E5%9B%BE%E8%B0%B1.png)](https://github.com/CL0610/Java-concurrency/blob/master/Java%E5%B9%B6%E5%8F%91%E7%9F%A5%E8%AF%86%E5%9B%BE%E8%B0%B1.png)

## Multithreading

*   ["Summary of 40 Java Multithreading Problems"](http://www.importnew.com/18459.html)

## Thread safety

*   ["Concurrent Java Programming - Introduction to Thread Safety and Solution Mechanisms"](https://www.cnblogs.com/zhanht/p/5450325.html)

## Consistency, transaction

### Transaction ACID features

*   ["Database ACID Features"](https://blog.csdn.net/u012440687/article/details/52116108)

### Transaction isolation level

*   Uncommitted read: A transaction can read another uncommitted data and is prone to dirty reads.

*   Read submission: A transaction can read data only after another transaction has been submitted, but a non-repeatable read situation occurs (the read data is inconsistent), and an UPDATE operation occurs during the read process.</font> <font style="vertical-align: inherit;">(The default level for most databases is RC, such as SQL Server, Oracle), which cannot be changed when reading.

*   Repeatable reading: The same transaction ensures that the same data is obtained for each read, but does not guarantee that the original data is updated (phantom read) by other transactions. Mysql InnoDB is this level.

*   Serialization: serial processing of all things (sacrificing efficiency)

*   [Understanding the Four Isolation Levels of a Business](https://blog.csdn.net/qq_33290787/article/details/51924963)

*   [Four characteristics of database transactions and transaction isolation levels](https://www.cnblogs.com/z-sm/p/7245981.html)

*   ["InnoDB's phantom reading problem"](http://blog.sina.com.cn/s/blog_499740cb0100ugs7.html)

    *   The example of phantom reading is very clear.
    *   Solve with SELECT ... FOR UPDATE.
*   ["An article with you to read MySQL and InnoDB"](http://database.51cto.com/art/201804/570101.htm)

    *   Graphical dirty reading, non-repeatable reading, phantom reading problems.

### MVCC

*   ["[mysql] some understanding of MVCC in innodb"](https://www.cnblogs.com/chenpingzhao/p/5065316.html)

    *   The MVCC in innodb is used at the Repeatable-Read isolation level.
    *   MVCC produces phantom issues (updated exceptions.)
*   ["Easy understanding MYSQL MVCC implementation mechanism"](https://blog.csdn.net/whoamiyang/article/details/51901888)

    *   MVCC control is achieved by hiding the version column, a record creation time, a record deletion time, and the time
    *   Only operate on lines that are smaller (or equal) than the current version.

## lock

### Locks and synchronization classes in Java

*   ["Lock Classification in Java"](https://www.cnblogs.com/qifengshi/p/6831055.html)

    *   Mainly includes synchronized, ReentrantLock, and ReadWriteLock.
*   ["Java Concurrency AQS Detailed"](https://www.cnblogs.com/waterystone/p/4920797.html)

*   ["Signal Semaphore in Java"](http://cuisuqiang.iteye.com/blog/2020146)

    *   Quantity control
    *   Apply with acquire, apply for not blocked; release with release.
*   ["Mutex vs Semaphore in Java Development"](https://www.cnblogs.com/davidwang456/p/6094947.html)

    *   Simply put, Mutex is exclusive. Only one resource can be obtained. Semaphore is also exclusive, but it can define multiple objects that can be accessed.

### Fair lock & non-fair lock

The role of the fair lock is to execute in strict accordance with the order in which the threads are started, and no other thread is allowed to queue execution; non-fair locks are allowed to be queued.

*   [Fair and Unfair Locks](https://blog.csdn.net/EthanWhite/article/details/55508357)
    *   ReentrantLock and synchronized are both non-fair locks by default.</font> <font style="vertical-align: inherit;">ReentrantLock can be set to fair lock.

### Pessimistic lock

Pessimistic locking, if used improperly (with too many locks), can cause large areas of service to wait.</font> <font style="vertical-align: inherit;">It is recommended to use optimistic locking + retries first.

*   ["[MySQL] Pessimistic Lock & Optimistic Lock"](https://www.cnblogs.com/zhiqian-ali/p/6200874.html)

    *   Optimistic locking method: version number + retry method
    *   Pessimistic locking: row locking via select ... for update (unreadable, non-writable, and share lock read-unreadable).
*   ["Mysql query statement using select.. for update database deadlock analysis"](https://www.cnblogs.com/Lawson/p/5008741.html)

    *   Although the innodb storage engine oracle's intrinsic lock is a lock line, it is internally locked.
    *   Different index conditions that lock the same data can cause deadlocks.
*   ["Mysql concurrent classic deadlock causes and solutions"](https://www.cnblogs.com/zejin2008/p/5262751.html)

### Optimistic Lock & CAS

*   ["An Optimistic Lock Implementation - CAS"](http://www.importnew.com/20472.html)
    *   It is similar to the MySQL optimistic lock method, but it is compared with the original value.

### ABA issues

Due to high concurrency, under CAS, this A may not be A after updating.</font> <font style="vertical-align: inherit;">It can be solved by the version number, similar to the optimistic lock mentioned in Mysql above.

*   [Java CAS and ABA Issues](https://www.cnblogs.com/549294286/p/3766717.html)
*   ["ABA Problems and Avoidance in Java"](https://blog.csdn.net/li954644351/article/details/50511879)
    *   AtomicStampedReference and AtomicStampedReference.

### CopyOnWrite container

Concurrent reads can be made to the CopyOnWrite container without the need for locking.</font> <font style="vertical-align: inherit;">The CopyOnWrite concurrent container is used to read multiple writes and fewer concurrent scenes.</font> <font style="vertical-align: inherit;">For example, whitelists, blacklists, and visits and update scenarios for product categories are not suitable for scenarios that require strong data consistency.

*   ["Copy-On-Write Map Implementation in JAVA"](https://www.cnblogs.com/hapjin/p/4840107.html)

    *   Reading and writing are separated, reading occurs on the original data, and writing occurs on the copy.
    *   Without locking, consistency is finally achieved through consistency.
*   [Chat Concurrency - Copy-On-Write Container in Java](https://blog.csdn.net/a494303877/article/details/53404623)

### RingBuffer

*   ["Thread-safe, lock-free RingBuffer implementation [a read thread, a write thread]"](http://www.cnblogs.com/l00l/p/4115001.html)

### Reentrant Locks & Non-Reentrant Locks

*   [Reentrant and Non-Reentrant Locks](https://www.cnblogs.com/dj3839/p/6580765.html)

    *   Examples of reentrant locks and non-reentrant locks are illustrated by simple code.
    *   Reentrant locks mean that the same thread can regain previously acquired locks.
    *   Reentrant locks allow users to avoid deadlocks.
    *   Reentrant locks in Java: synchronized and java.util.concurrent.locks.ReentrantLock
*   ["ReenTrantLock reentrant lock (and the difference between synchronized) summary"](https://www.cnblogs.com/baizhanshi/p/7211802.html)

    *   Synchronized easy to use, the compiler to lock, is a non-fair lock.
    *   ReenTrantLock is flexible and lock fairness can be customized.
    *   In the same locked scenario, it is recommended to use synchronized.

### Mutexes & shared locks

Mutexes: Only one thread can acquire a lock at the same time.</font> <font style="vertical-align: inherit;">For example, ReentrantLock is a mutex, and write locks in ReadWriteLock are mutexes.</font> <font style="vertical-align: inherit;">Shared locks: There can be multiple or simultaneous locks.</font> <font style="vertical-align: inherit;">For example, Semaphore, CountDownLatch are shared locks, and read locks in ReadWriteLock are shared locks.

*   ["ReadWriteLock Scene Application"](https://www.cnblogs.com/liang1101/p/6475555.html)

### Deadlock

*   ["Reasonable explanation of the four necessary conditions for "deadlock"](https://blog.csdn.net/yunfenglw/article/details/45950305)

    *   Mutually exclusive, held, inalienable, inalienable.
*   [How can Java view the deadlock?](https://blog.csdn.net/u014039577/article/details/52351626)

    *   JConsole recognizes deadlocks.
*   [Java multi-threaded series: deadlock and detection](https://blog.csdn.net/bohu83/article/details/51135061)

    *   Jstack can display deadlocks.

# operating system

## Principle of computer

*   ["Basic knowledge of operating system - principle, type and structure of operating system"](https://segmentfault.com/a/1190000003692840)

## CPU

### Multi-level cache

A typical CPU has three levels of cache. The closer it is to the core, the faster and the smaller the space.</font> <font style="vertical-align: inherit;">L1 is generally 32k, L2 is generally 256k, and L3 is generally 12M.</font> <font style="vertical-align: inherit;">The memory speed requires 200 CPU cycles and the CPU cache requires 1 CPU cycle.

*   ["Understanding CPU Cache and Pseudo Sharing from a Java Perspective"](https://blog.csdn.net/zero__007/article/details/54089730)

## process

TODO

## Threads

*   ["Thread life cycle and state transition details"](https://blog.csdn.net/asdf_1024/article/details/78978437)

## Correspondence

*   ["Terminating Python Coroutines--Implementation from Yield to actor Model"](https://www.thinksaas.cn/group/topic/839375/)
    *   Thread scheduling is the responsibility of the operating system. Coroutine scheduling is the responsibility of the program.
    *   Compared with threads, coroutines reduce unnecessary operating system switching.
    *   In fact, when switching to an IO operation is more meaningful, (because the IO operation does not occupy the CPU), if no IO operation is encountered, switch according to the time slice.

## Linux

*   [Linux Command Encyclopedia](http://www.runoob.com/linux/linux-command-manual.html)

# Design Patterns

## Six principles of design patterns

*   [The Six Principles of Design Patterns](https://blog.csdn.net/q291611265/article/details/48465113)
    *   The principle of opening and closing: open to the extension, close to the modification, use more abstract classes and interfaces.
    *   Lie substitution principle: the base class can be replaced by subclasses, use abstract class inheritance, do not use concrete class inheritance.
    *   Relying on the principle of reversal: to rely on abstraction, not relying on the specific, programming for the interface, not for programming.
    *   Interface isolation principle: Using multiple isolated interfaces is better than using a single interface to establish a minimal interface.
    *   Dimit's Law: A software entity should interact with other entities as little as possible and establish links through intermediate classes.
    *   Synthetic reuse principles: Use synthetic/aggregate as much as possible instead of using inheritance.

## 23 common design patterns

*   ["Design Patterns"](http://www.runoob.com/design-pattern/design-pattern-tutorial.html)
*   ["23 kinds of design patterns full analysis"](https://www.cnblogs.com/susanws/p/5510229.html)

## Application scenario

*   ["Detailed Design Patterns in the JDK"](http://blog.jobbole.com/62314/)

    *   Structural mode:

        *   Adapter: Used to convert an interface to another interface, such as java.util.Arrays#asList().
        *   Bridge mode: This mode decouples the implementation of abstract and abstract operations, so that the abstraction and implementation can be independently changed, such as JDBC;
        *   Combined mode: Makes the client seem to have the same combination of individual objects and objects.</font> <font style="vertical-align: inherit;">In other words, a certain type of method also accepts its own type as parameters, such as Map.putAll, List.addAll, Set.addAll.
        *   Decorator pattern: Dynamically adds an extra function to an object, which is an alternative to subclasses, such as java.util.Collections#checkedList|Map|Set|SortedSet|SortedMap.
        *   Fragmentation mode: use caching to speed up the access time of a large number of small objects, such as valueOf(int).
        *   Proxy mode: The proxy mode is to replace a complex or time-consuming object with a simple object, such as java.lang.reflect.Proxy
    *   Create mode:

        *   Abstract factory pattern: The abstract factory pattern provides a protocol to generate a series of related or independent objects without specifying the concrete object type, such as java.util.Calendar#getInstance().
        *   Builder: A new class is defined to build an instance of another class to simplify the creation of complex objects such as: java.lang.StringBuilder#append().
        *   Factory method: that</font> </font>**a return**<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">* back to the specific object methods, rather than several, such as java.lang.Object # toString (), java.lang.Class # newInstance ().
        *   Prototype mode: Makes an instance of a class generate its own copy, such as: java.lang.Object#clone().
        *   Singleton mode: There is only one instance globally, such as java.lang.Runtime#getRuntime().
    *   Behavior pattern:

        *   Chain of Responsibility: By delegating requests from an object to the next object in the chain until the request is processed, decoupling between objects is achieved.</font> <font style="vertical-align: inherit;">Such as javax.servlet.Filter#doFilter().
        *   Command mode: encapsulates operations into objects for storage, delivery, and return, such as: java.lang.Runnable.
        *   Interpreter mode: defines the syntax of a language, and then parses the corresponding syntax statement, such as java.text.Format, java.text.Normalizer.
        *   Iterator mode: Provides a consistent method for sequentially accessing objects in a collection, such as java.util.Iterator.
        *   Mediator pattern: java.lang.reflect.Method#invoke() by using an intermediate object for message distribution and reducing the direct dependency between classes.
        *   Empty object patterns: such as java.util.Collections#emptyList().
        *   Observer pattern: It allows an object to send messages to interested objects flexibly, such as java.util.EventListener.
        *   Template method pattern: Allows subclasses to override part of the method instead of the entire rewrite, such as java.util.Collections#sort().
*   ["Spring-related design patterns summary"](https://www.cnblogs.com/hwaggLee/p/4510687.html)

*   ["Design Patterns Used by Mybatis"](https://blog.csdn.net/u012387062/article/details/54719114)

## Singleton mode

*   [Three Implementations of the Singleton Model and Their Advantages and Disadvantages](https://blog.csdn.net/YECrazy/article/details/79481964)
*   [Singleton Pattern - Reflection - Preventing Serialization from Destroying Singleton Patterns](https://www.cnblogs.com/ttylinux/p/6498822.html)
    *   Use enumeration types.

## Chain of responsibility model

TODO

## MVC

*   ["MVC Mode"](http://www.runoob.com/design-pattern/mvc-pattern.html)
    *   Model - view - controller

## IOC

*   [Understanding the IOC](https://www.zhihu.com/question/23277575)
*   ["ICO Understanding and Interpretation"](https://www.cnblogs.com/NancyStartOnce/p/6813162.html)
    *   Positive control: Tradition through new.</font> <font style="vertical-align: inherit;">Reverse control, inject the object through the container.
    *   Role: For module decoupling.
    *   DI: Dependency Injection, that is, dependency injection, is only concerned with resource usage and does not care about the source of resources.

## AOP

*   [Easy to understand AOP (face-oriented programming)](https://my.oschina.net/yanquan345/blog/203415)
*   ["Spring AOP Detailed"](https://www.cnblogs.com/hongwz/p/5764917.html)
*   ["Spring AOP Implementation Principles"](http://www.importnew.com/24305.html)
    *   The dynamic proxy used by Spring AOP is mainly in two ways: JDK dynamic proxy and CGLIB dynamic proxy.
*   [Spring AOP Implementation Principles and CGLIB Applications](https://www.ibm.com/developerworks/cn/java/j-lo-springaopcglib/)
    *   The principle of handling the AOP proxy class in the Spring AOP framework is: If the target object's implementation class implements the interface, Spring AOP will use the JDK dynamic proxy to generate the AOP proxy class; if the target object's implementation class does not implement the interface, Spring AOP will Use CGLIB to generate AOP proxy classes

## UML

*   ["UML Tutorial"](https://www.w3cschool.cn/uml_tutorial/)

## Microservice idea

*   ["Micro Service Architecture Design"](https://www.cnblogs.com/wintersun/p/6219259.html)
*   ["Microservice Architecture Technology Stack Selection Manual"](http://www.infoq.com/cn/articles/micro-service-technology-stack)

### Conway Law

*   ["The Theoretical Basis of Microservice Architecture - Conway's Law"](https://yq.aliyun.com/articles/8611)

    *   Rule One: Organizational communication methods will be expressed through system design, which means that the layout and organizational structure of the architecture will be similar.
    *   Law 2: Time is not possible to do more perfect one thing, but there is always time to finish one thing.</font> <font style="vertical-align: inherit;">Can't get fat in one go, but you can get it first.
    *   Law 3: There are potentially heterogeneous homomorphic characteristics between linear systems and linear organizational structures.</font> <font style="vertical-align: inherit;">Get melons and become independent autonomous subsystems to reduce communication costs.
    *   Law 4: Large system organizations are always more decomposed than small systems.</font> <font style="vertical-align: inherit;">All the time will be divided, divide and rule.
*   ["Microservice Architecture Core 20"](https://static.geekbang.org/PDF-%E4%BF%AE%E6%94%B9%E7%89%88-%E6%9E%81%E5%AE%A2%E6%97%B6%E9%97%B4-%E5%9B%BE%E7%89%87-%E6%9D%A8%E6%B3%A2-%E5%BE%AE%E6%9C%8D%E5%8A%A1%E6%9E%B6%E6%9E%84.pdf)

# Operation & Statistics & Technical Support

## General monitoring

*   ["Tencent Business System Monitoring Practice Road"](https://blog.csdn.net/enweitech/article/details/77849205)

    *   Monitoring methods: active, passive, bypass (such as public opinion monitoring)
    *   Monitoring type: Basic monitoring, server monitoring, client monitoring, monitoring, customer monitoring
    *   Monitoring objectives: full, block, accurate
    *   Core indicators: request volume, success rate, time-consuming
*   ["Open source or commercial?</font> <font style="vertical-align: inherit;">Top Ten Yunyunwei Monitoring Tools Hengping Review](https://www.oschina.net/news/67525/monitoring-tools)

    *   Zabbix, Nagios, Ganglia, Zenoss, Open-falcon, Monitor Po, 360 Website Service Monitoring, Alibaba Cloud Monitoring, Baidu Cloud Observation, Little Bee Website Monitoring, etc.
*   ["Monitoring alarm system construction and secondary development experience"](http://developer.51cto.com/art/201612/525373.htm)

**Command line monitoring tool**

*   ["Common command line monitoring tool"](https://coderxing.gitbooks.io/architecture-evolution/di-er-pian-ff1a-feng-kuang-yuan-shi-ren/44-an-quan-yu-yun-wei/445-fu-wu-qi-zhuang-tai-jian-ce/4451-ming-ling-xing-gong-ju.html)

    *   Top, sar, tsar, nload
*   [20 Command Line Tools to Monitor Linux System Performance](http://blog.jobbole.com/96846/)

*   ["Detailed Usage of JVM Performance Tuning Monitoring Tools jps, jstack, jmap, jhat, jstat, hprof"](https://my.oschina.net/feichexia/blog/196575)

## APM

APM — Application Performance Management

*   [Dapper, Tracking System for Large-Scale Distributed Systems](http://bigbully.github.io/Dapper-translation/)

*   [CNCF OpenTracing](http://opentracing.io)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">,</font> </font>[Chinese version](https://github.com/opentracing-contrib/opentracing-specification-zh)

*   The main open source software, alphabetically sort

    *   [Apache SkyWalking](https://github.com/apache/incubator-skywalking)
    *   [CAT](https://github.com/dianping/cat)
    *   [CNCF jaeger](https://github.com/jaegertracing/jaeger)
    *   [Pinpoint](https://github.com/naver/pinpoint)
    *   [Zipkin](https://github.com/openzipkin/zipkin)
*   ["Open source APM technology selection and actual combat"](http://www.infoq.com/cn/articles/apm-Pinpoint-practice)

    *   Mainly based on Google's Dapper (large-scale distributed system tracking system) idea.

## Statistical Analysis

*   ["The basis of traffic statistics: buried point"](https://zhuanlan.zhihu.com/p/25195217)

    *   Common metrics: visits and visitors, length of stay, bounce rate, exit rate, conversion rate, engagement
*   ["Statistical tools, buried targets and buried contents commonly used by APP sites"](http://www.25xt.com/company/17066.html)

    *   Third-party statistics: UFIDA, Baidu Mobile, Rubik's Cube, App Annie, talking data, and other data.
*   ["The United States Mission Review front-end no trace buried practice"](https://tech.meituan.com/mt-mobile-analytics-practice.html)

    *   The so-called no trace, that is, the acquisition node is configured through a visualization tool, and the front end automatically analyzes the configuration and reports buried data, instead of hard coding.

## 

*   [What is Continuous Integration?</font> <font style="vertical-align: inherit;">》](http://www.ruanyifeng.com/blog/2015/09/continuous-integration.html)
*   [8 Popular Continuous Integration Tools](https://www.testwo.com/article/1170)

### Jenkins

*   ["Using Jenkins for Continuous Integration"](https://www.liaoxuefeng.com/article/001463233913442cdb2d1bd1b1b42e3b0b29eb1ba736c5e000)

### Environmental separation

Development, testing, and production environment separation.

*   ["Basic understanding and area of ​​development environment, production environment, and test environment"](https://my.oschina.net/sancuo/blog/214904)

## Automation operation and maintenance

### Ansible

*   [Ansible Chinese Authoritative Guide](http://www.ansible.com.cn/)
*   ["Ansible Basic Configuration and Enterprise Project Practical Cases"](https://www.cnblogs.com/heiye123/articles/7855890.html)

### Puppet

*   ["Automatic maintenance tools - detailed puppet"](https://www.cnblogs.com/keerya/p/8040071.html)

### Chef

*   ["Chef Installation and Use"](https://www.ibm.com/developerworks/cn/cloud/library/1407_caomd_chef/)

## test

### TDD theory

*   [Deep Interpretation - TDD (Test Driven Development)](https://www.jianshu.com/p/62f16cd4fef3)
    *   Based on test case coding function code, XP (Extreme Programming) core practice.
    *   Benefits: Focus on one point at a time, reduce the burden of thinking; meet changes in demand or improve code design; clarify requirements in advance;

### unit test

*   ["Java Unit Testing JUnit"](https://www.cnblogs.com/happyzm/p/6482886.html)
*   ["Compare JUnit 4 with TestNG"](https://blog.csdn.net/hotdust/article/details/53406086)
    *   TestNG overrides JUnit features for more complex scenarios.
*   ["Unit test major test function point"](https://blog.csdn.net/wqetfg/article/details/50900512)
    *   Module interface testing, local data structure testing, path testing, error handling testing, and boundary condition testing.

### pressure test

*   ["Apache ab test user guide"](https://blog.csdn.net/blueheart20/article/details/52170790)
*   ["Large Website Stress Testing and Optimization Program"](https://www.cnblogs.com/binyue/p/6141088.html)
*   ["10 mainstream pressure / load / performance test tool recommended"](http://news.chinabyte.com/466/14126966.shtml)
*   ["True traffic pressure measurement tool tcpcopy application analysis"](http://quentinxxz.iteye.com/blog/2249799)
*   ["nGrinder Easy-to-use tutorial"](https://www.cnblogs.com/jwentest/p/7136727.html)

### Full-link pressure test

*   ["Jingdong 618: Upgrade full-link pressure test program to create ForceBot for military exercises"](http://www.infoq.com/cn/articles/jd-618-upgrade-full-link-voltage-test-program-forcebot)
*   ["Hungry? Exploration and Practice of Full Link Pressure Measurement"](https://zhuanlan.zhihu.com/p/30306892)
*   ["Four languages, eight frameworks | Drip drop full-link pressure measurement solution"](https://zhuanlan.zhihu.com/p/28355759)
*   ["Full-Link Pressure Test Experience"](https://www.jianshu.com/p/27060fd61f72)

### A/B, grayscale, blue-green test

*   [Technical Dry Goods | AB Testing and Grayscale Distribution Exploration and Practice](https://testerhome.com/topics/11165)

*   ["nginx grayscale publishing based on IP"](http://blog.51cto.com/purplegrape/1403123)

*   [Blue Green Deployment, A/B Testing, and Grayscale Publishing](https://www.v2ex.com/t/344341)

## Virtualization

*   ["Comparison of the advantages and disadvantages of three VPS virtualization technologies, OpenVZ, Xen and KVM"](https://blog.csdn.net/enweitech/article/details/52910082)

### KVM

*   ["KVM Detailed, too detailed and in-depth, classic"](http://blog.chinaunix.net/uid-20201831-id-5775661.html)
*   ["[text]KVM virtual machine installation explain"](https://www.coderxing.com/kvm-install.html)

### Xen

*   ["Xen Virtualization Fundamentals"](https://www.cnblogs.com/sddai/p/5931201.html)

### OpenVZ

*   [Open Source Linux OpenVZ Quick Start Guide](https://blog.csdn.net/longerzone/article/details/44829255)

## Container technology

### Docker

*   ["Several Diagrams Help You Understand Docker Fundamentals and Quick Start"](https://www.cnblogs.com/SzeCheng/p/6822905.html)
*   [Docker Core Technology and Implementation Principles](https://draveness.me/docker)
*   [Docker Tutorial](http://www.runoob.com/docker/docker-tutorial.html)

## Cloud technology

### OpenStack

*   ["OpenStack architecture knowledge combing"](https://www.cnblogs.com/klb561/p/8660264.html)

## DevOps

*   ["What tells you exactly what DevOps is?</font> <font style="vertical-align: inherit;">》](https://www.cnblogs.com/jetzhang/p/6068773.html)
*   [DevOps Explained](http://www.infoq.com/cn/articles/detail-analysis-of-devops)

## Document management

*   [Confluence - Charge Document Management System](http://www.confluence.cn/)
*   GitLab?
*   Wiki

# Middleware

## Web Server

### Nginx

*   ["Basic Learning of Ngnix - Comparison of Multiple Processes and Apache"](https://blog.csdn.net/qq_25797077/article/details/52200722)

    *   Nginx achieves high concurrency through asynchronous non-blocking event handling mechanisms.</font> <font style="vertical-align: inherit;">Apache monopolizes one thread per request and consumes system resources.
    *   Event-driven is suitable for IO intensive services (Nginx), multi-process or thread-adapted to CPU-intensive services (Apache), so Nginx is suitable for reverse proxy, not web server use.
*   ["Comparisons and advantages and disadvantages of nginx and Apache"](https://www.cnblogs.com/cunkouzh/p/5410154.html)

    *   Nginx is only suitable for static and reverse proxies and is not suitable for handling dynamic requests.

### OpenResty

*   [Official website](http://openresty.org/cn/)
*   ["On OpenResty"](http://www.linkedkeeper.com/detail/blog.action?bid=1034)
    *   The Lua module can be developed on Nginx.

### Apache Httpd

*   [Official website](http://httpd.apache.org/)

### Tomcat

#### Architecture principle

*   ["Detailed TOMCAT Principles and Request Process"](https://www.cnblogs.com/hggen/p/6264475.html)

*   ["The detailed Tomcat server principle"](https://www.cnblogs.com/crazylqy/p/4706223.html)

*   ["Tomcat System Architecture and Design Patterns, Part 1: How It Works"](https://www.ibm.com/developerworks/cn/java/j-lo-tomcat1/)

*   ["Four Diagrams Take You Through Tomcat System Architecture"](https://blog.csdn.net/xlgen157387/article/details/79006434)

*   ["JBoss vs. Tomcat: Choosing A Java Application Server"](https://www.futurehosting.com/blog/jboss-vs-tomcat-choosing-a-java-application-server/)

    *   Tomcat is a lightweight Serverlet container that does not implement all JEE features (such as persistence and transaction processing) but can be replaced by other components such as Srping.
    *   Jboss implements all JEE features, free software open source, and documentation fees.

#### Tuning plan

*   [Tomcat Tuning Solution](https://www.cnblogs.com/sunfenqing/p/7339058.html)

    *   Start NIO mode (or APR); adjust thread pool; disable AJP connector (Nginx+tomcat architecture, no AJP required);
*   ["tomcat http protocol and ajp protocol"](http://blog.chinaunix.net/uid-20662363-id-3012760.html)

*   [AJP vs. HTTP Comparison and Analysis](http://dmouse.iteye.com/blog/1354527)

    *   The AJP protocol (port 8009) is used to reduce the number of connections (front-end) to the front-end Server (such as Apache, which also needs to support the AJP protocol), and to increase performance through long connections.
    *   When concurrency is high, the AJP protocol is better than the HTTP protocol.

### Jetty

*   ["How Jetty Works and Comparison with Tomcat"](https://www.ibm.com/developerworks/cn/java/j-lo-jetty/)
*   ["Compared advantages of jetty and tomcat"](https://blog.csdn.net/doutao6677/article/details/51957288)
    *   Architecture comparison: Jetty's architecture is much simpler than Tomcat's.
    *   Performance comparison: Jetty and Tomcat have little difference in performance. Jetty uses NIO to end up with more advantages in handling I/O requests. Tomcat uses BIO to handle I/O requests by default. Tomcat is suitable for handling a few very busy links and handles static resources. Poor performance.
    *   Other aspects: The application of Jetty is faster, simpler to modify, and better supported by the new Servlet specification; Tomcat supports JEE and Servlet more comprehensively.

## Caching

*   ["Cache invalidation strategy (the difference between FIFO, LRU, LFU algorithm)"](https://blog.csdn.net/clementad/article/details/48229243)

### Local cache

*   [HashMap Local Cache](https://coderxing.gitbooks.io/architecture-evolution/di-er-pian-ff1a-feng-kuang-yuan-shi-ren/42-xing-neng-zhi-ben-di-huan-cun/421-ying-yong-ceng-ben-di-huan-cun/4211.html)

*   [EhCache Local Cache](https://coderxing.gitbooks.io/architecture-evolution/di-er-pian-ff1a-feng-kuang-yuan-shi-ren/42-xing-neng-zhi-ben-di-huan-cun/421-ying-yong-ceng-ben-di-huan-cun/4212-ehcache.html)

    *   On-heap, off-heap, disk level 3 cache.
    *   Can be set according to the amount of cache space.
    *   According to time, number of times and other expiration strategies.
*   [Guava Cache](https://coderxing.gitbooks.io/architecture-evolution/di-er-pian-ff1a-feng-kuang-yuan-shi-ren/42-xing-neng-zhi-ben-di-huan-cun/421-ying-yong-ceng-ben-di-huan-cun/4213-guava-cache.html)

    *   Simple and lightweight, no heap, disk cache.
*   [Nginx Local Cache](https://coderxing.gitbooks.io/architecture-evolution/di-er-pian-ff1a-feng-kuang-yuan-shi-ren/42-xing-neng-zhi-ben-di-huan-cun/422-fu-wu-duan-ben-di-huan-cun/nginx-ben-di-huan-cun.html)

*   ["Pagespeed - lazy tool, server-side acceleration"](https://coderxing.gitbooks.io/architecture-evolution/di-er-pian-ff1a-feng-kuang-yuan-shi-ren/42-xing-neng-zhi-ben-di-huan-cun/422-fu-wu-duan-ben-di-huan-cun/4222-pagespeed.html)

## Client Cache

*   [Browser Side Cache](https://coderxing.gitbooks.io/architecture-evolution/di-er-pian-ff1a-feng-kuang-yuan-shi-ren/42-xing-neng-zhi-ben-di-huan-cun/423-ke-hu-duan-huan-cun.html)

    *   Mainly using the Cache-Control parameter.
*   ["H5 and Mobile WebView Cache Mechanism Analysis and Combat"](https://mp.weixin.qq.com/s/qHm_dJBhVbv0pJs8Crp77w)

## Server cache

### Web Cache

*   [Nuster](https://github.com/jiangwenyuan/nuster)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">- nuster cache
*   [Varnish](https://github.com/varnishcache/varnish-cache)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">- varnish cache
*   [Squid](https://github.com/squid-cache/squid)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">- squid cache

### Memcached

*   [Memcached Tutorial](http://www.runoob.com/Memcached/Memcached-tutorial.html)

*   ["In-depth understanding of the principle of Memcached"](https://blog.csdn.net/chenleixing/article/details/47035453)

    *   Use multiplexing techniques to increase concurrency.
    *   The slab allocation algorithm: memcached allocates memory space for Slab, the default is 1MB.</font> <font style="vertical-align: inherit;">After allocating to Slab, the slab of the slab is divided into chunks of the same size. Chunk is the memory space used to cache the records. The chunk size is incremented by 1.25 times by default.</font> <font style="vertical-align: inherit;">The advantage is that it will not frequently apply for memory and improve IO efficiency. The disadvantage is that there will be a certain amount of memory waste.
*   ["How Memcached Software Works"](https://www.jianshu.com/p/36e5cd400580)

*   ["Memcache Technology Sharing: Introduction, Usage, Storage, Algorithms, Optimization, Hit Rate"](http://zhihuzeye.com/archives/2361)

*   [Differences between add, set, and replace in memcache](https://blog.csdn.net/liu251890347/article/details/37690045)

    *   The difference is that when the key exists or does not exist, the return value is true and false.
*   [**"Comprehensive Analysis of Memcached"**](https://pan.baidu.com/s/1qX00Lti?errno=0&errmsg=Auth%20Login%20Sucess&&bduss=&ssnerror=0&traceid=)

### Redis

*   [Redis Tutorial](http://www.runoob.com/redis/redis-tutorial.html)

*   ["The principle of redis bottom"](https://blog.csdn.net/wcf373722432/article/details/78678504)

    *   Using ziplists to store linked lists, ziplists are a kind of compressed list, which has the advantage of saving more memory because everything it stores is in a contiguous area of ​​memory.
    *   Skiplist is used to store ordered collection objects, search on high level, complexity of time and red-black tree, implementation is easy, lock-free and concurrency is good.
*   ["Redis Persistence Method"](http://doc.redisfans.com/topic/persistence.html)

    *   RDB mode: Periodically backs up snapshots and is commonly used for disaster recovery.</font> <font style="vertical-align: inherit;">Advantages: Backing up through the fork process does not affect the speed of the main process and RDB when recovering large data sets faster than AOF recovery.</font> <font style="vertical-align: inherit;">Disadvantages: Will lose data.
    *   AOF mode: Save the operation log mode.</font> <font style="vertical-align: inherit;">Advantages: Less data loss during recovery, disadvantages: large files, slow response.
    *   It can also be used in combination.
*   ["Distributed Cache - Sequence 3 - Atomic Operations and CAS Optimistic Locking"](https://blog.csdn.net/chunlongyu/article/details/53346436)

#### Structure

*   [Redis Single-threaded Architecture](https://blog.csdn.net/sunhuiliang85/article/details/73656830)

#### Recovery strategy

*   ["Redis Recovery Strategy"](https://blog.csdn.net/qq_29108585/article/details/63251491)

### Tair

*   [Official website](https://github.com/alibaba/tair)
*   ["The Comparison of Tair and Redis"](http://blog.csdn.net/farphone/article/details/53522383)
*   Features: You can configure the number of backup nodes, asynchronously to the backup node
*   Consistent hashing algorithm.
*   Architecture: Similar to the design concept of Hadoop, Configserver, DataServer, and Configserver are used to detect heartbeats. Configserver also has a master/slave relationship.

Several storage engines:

*   MDB, full memory, can be used to store data such as Session.
*   Rdb (similar to Redis), lightweight, removes operations like aof, supports Restfull operations
*   LDB (LevelDB storage engine), persistent storage, LDB as a persistence of rdb, google implementation, more efficient, theoretical basis is the LSM (Log-Structured-Merge Tree) algorithm, now modify the data in memory, reach a certain amount (and Memory aggregated old data is written to disk together. Write to disk and storage is more efficient. The county compares the hash algorithm.
*   Tair uses shared memory to store data. If the service goes down (not the server), the data is still available after the service is restarted.

## message queue

*   [Message Queue - Push/Pull Mode Learning & ActiveMQ and JMS Learning](https://www.cnblogs.com/charlesblc/p/6045238.html)

    *   The RabbitMQ consumer defaults to push mode (also supports pull mode).
    *   Kafka defaults to pull mode.
    *   Push mode: The advantage is that the message can be sent to the consumer as soon as possible. The disadvantage is that if the consumer's processing power cannot keep up, the consumer's buffer may overflow.
    *   Pull: The advantage is that the consumer can pull it off according to its processing power. The disadvantage is that it will increase the message delay.
*   ["Comparison of Kafka, RabbitMQ, RocketMQ and Other Message Middleware - Message Sending Performance and Difference"](https://blog.csdn.net/yunfeng482/article/details/72856762)

### Message bus

The message bus is equivalent to a layer of encapsulation on the message queue, unified entrance, unified management and control, simplifying the access cost.

*   [Message Bus VS Message Queue](https://blog.csdn.net/yanghua_kobe/article/details/43877281)

### Order of messages

*   [How to ensure the order of consumers to receive messages](https://www.cnblogs.com/cjsblog/p/8267892.html)

### RabbitMQ

Supports transactions, push and pull modes are all supported, and are suitable for scenarios requiring reliable message transmission.

*   ["RabbitMQ Application Scenarios and Introduction to Basic Principles"](https://blog.csdn.net/whoamiyang/article/details/54954780)
*   [Message Queue RabbitMQ](https://www.jianshu.com/p/79ca08116d57)
*   ["RabbitMQ message confirmation mechanism (transaction + Confirm)"](https://blog.csdn.net/u013256816/article/details/55515234)

### RocketMQ

Java implementation, push and pull modes are all supported, and the throughput is lower than Kafka.</font> <font style="vertical-align: inherit;">The order of messages can be guaranteed.

*   [RocketMQ Reality Quick Start](https://www.jianshu.com/p/824066d70da8)

### ActiveMQ

Pure Java implementation, compatible with JMS, can be embedded in Java applications.

*   ["Introduction to ActiveMQ Message Queue"](https://www.cnblogs.com/wintersun/p/3962302.html)

### Kafka

High throughput, pull mode.</font> <font style="vertical-align: inherit;">Suitable for high IO scenarios, such as log synchronization.

*   [Official website](http://kafka.apache.org/)
*   ["Compared with the message queues, Kafka's in-depth analysis, everyone's recommendation, wonderful good!</font> <font style="vertical-align: inherit;">》](https://blog.csdn.net/allthesametome/article/details/47362451)
*   ["Introduction and Example of Kafka Partitioning Mechanism"](http://lxw1234.com/archives/2015/10/538.htm)

### Redis message push

Producer and consumer patterns are completely client-side behaviors, list and pull modes are implemented, blocking waits for blpop instructions.

*   ["Redis Study Notes 10: Redis Used as Message Queue"](https://blog.csdn.net/qq_34212276/article/details/78455004)

### ZeroMQ

TODO

## Scheduled scheduling

### Stand-alone scheduled scheduling

*   ["Linux regular task cron configuration"](https://www.cnblogs.com/shuaiqing/p/7742382.html)

*   ["Linux cron operation principle"](https://my.oschina.net/daquan/blog/483305)

    *   Fork process + sleep poll
*   [Quartz Usage Summary](https://www.cnblogs.com/drift-ice/p/3817269.html)

*   ["Quartz source code analysis ---- trigger start principle"](https://blog.csdn.net/wenniuwuren/article/details/42082981/)

*   ["quartz principle secret and source code interpretation"](https://www.jianshu.com/p/bab8e4e32952)

    *   Scheduled scheduling In the QuartzSchedulerThread code, while() loops indefinitely, every time the loop retrieves the trigger that the time will reach, and the corresponding job is fired until the scheduler thread is closed.

### Distributed timing scheduling

*   ["These excellent domestic distributed task scheduling system, you used a few?</font> <font style="vertical-align: inherit;">》](https://blog.csdn.net/qq_16216221/article/details/70314337)

    *   Opencron, LTS, XXL-JOB, Elastic-Job, Uncode-Schedule, Antares
*   ["The Basic Principles of Quartz Task Scheduling"](https://www.cnblogs.com/zhenyuyaodidiao/p/4755649.html)

    *   Quartz cluster, independent Quartz node does not communicate with another node or management node, but through the same database table to another Quartz application

## RPC

*   ["Implementing the RPC Framework from scratch - Principles and realization of RPC"](https://blog.csdn.net/top_code/article/details/54615853)

    *   Core roles: Server: The service provider exposing the service, Client: The service consumer calling the remote service, Registry: The registration center for service registration and discovery.
*   ["Performance Comparison of Distributed RPC Framework Performance Competition dubbo, motan, rpcx, gRPC, thrift"](https://blog.csdn.net/testcs_dn/article/details/78050590)

### Dubbo

*   [Official website](http://dubbo.apache.org/)
*   [The dubbo implementation principle is briefly introduced](https://www.cnblogs.com/steven520213/p/7606598.html)

** SPI ** TODO

### Thrift

*   [Official website](http://thrift.apache.org/)
*   ["Thrift RPC Explained"](https://blog.csdn.net/kesonyk/article/details/50924489)
    *   Supports multiple languages, defining interfaces through intermediate languages.

### gRPC

The server can be authenticated and encrypted. In an external network environment, data security can be guaranteed.

*   [Official website](https://grpc.io/)
*   ["RPC Principles You Should Know"](https://www.cnblogs.com/LBSer/p/4853234.html)

## Database middleware

### Sharding Jdbc

*   [Official website](http://shardingjdbc.io/)

## Log system

### Log collection

*   ["Build an ELKB Log Collection System from scratch"](http://cjting.me/misc/build-log-system-with-elkb/)
*   ["Establish a Simple Log Collection and Analysis System with ELK"](https://blog.csdn.net/lzw_2006/article/details/51280058)
*   ["Log Collection System - Inquiry"](https://www.cnblogs.com/beginmind/p/6058194.html)

## Configuration Center

*   [Apollo - Ctrip's Configuration Center Application](https://github.com/ctripcorp/apollo)

    *   Spring Boot and Spring Cloud
    *   Support push and pull mode update configuration
    *   Supports multiple languages
*   ["Using zookeeper to achieve unified configuration management"](https://blog.csdn.net/u011320740/article/details/78742625)

*   [Spring Cloud Config Distributed Configuration Center Tutorial](https://www.cnblogs.com/shamo89/p/8016908.html)

Servlet 3.0 Asynchronous Feature Available to Configuration Center Clients

*   ["New Features in servlet 3.0 - Asynchronous Processing"](https://www.cnblogs.com/dogdogwang/p/7151866.html)

## API Gateway

Main responsibilities: request forwarding, security authentication, protocol conversion, disaster recovery.

*   [API Gateway Those](http://yunlzheng.github.io/2017/03/14/the-things-about-api-gateway/)

*   ["About the background, architecture and landing plan of API gateway"](http://www.infoq.com/cn/news/2016/07/API-background-architecture-floo)

*   [Using Zuul to Build an API Gateway](https://blog.csdn.net/zhanglh046/article/details/78651993)

*   ["Kong Introduction to One of the HTTP API Gateway Selections"](https://mp.weixin.qq.com/s/LIq2CiXJQmmjBC0yvYLY5A)

# The internet

## protocol

### OSI Layer 7 Protocol

*   ["OSI seven-layer protocol model, TCP/IP four-layer model study notes"](https://www.cnblogs.com/Robin-YB/p/6668762.html)

### TCP/IP

*   ["Instantly explain TCP/IP protocol"](https://www.cnblogs.com/onepixel/p/7092302.html)
*   ["Three-way handshake and four waves in TCP protocol"](https://blog.csdn.net/whuslei/article/details/6667471/)

### HTTP

*   ["Details of the http protocol (super detailed)"](https://www.cnblogs.com/wangning528/p/6388464.html)

### HTTP2.0

*   ["Detailed Analysis of HTTP 2.0 Principles"](https://blog.csdn.net/zhuyiquan/article/details/69257126)
*   ["The basic unit of HTTP2.0 is binary frame"](https://blog.csdn.net/u012657197/article/details/77877840)
    *   Use binary frames for transmission.
    *   Multiplexing.

### HTTPS

*   ["https Principles of Popular Understanding"](https://www.cnblogs.com/zhangshitong/p/6478721.html)

    *   Using asymmetric encryption to negotiate encryption algorithms
    *   Use symmetric encryption to transfer data
    *   Use a certificate issued by a third party to encrypt the public key for secure transmission of the public key and prevent it from being altered by an intermediary.
*   [Eight Free SSL Certificates - Adding Https Security to Your Website for Free](https://blog.csdn.net/enweitech/article/details/53213862)

## Network model

*   ["The principles of web optimization must understand the five models of the I/O and the three working modes of the web."](http://blog.51cto.com/litaotao/1289790)

    *   Five I/O models: Blocking I/O, Non-blocking I/O, I/O Multiplexing, Event (Signal) Driven I/O, Asynchronous I/O, and the first four I/Os are synchronous operations, I/O The first stage of O is the same and the second stage is the same. The last one belongs to asynchronous operation.
    *   Three kinds of Web Server work methods: Prefork (multi-process), Worker mode (thread mode), Event mode.
*   [Summary of differences between select, poll, and epoll](http://www.cnblogs.com/Anker/p/3265058.html)

    *   Select, poll, and epoll are essentially synchronous I/O because they all need to be responsible for reading and writing after the read/write event is ready. This means that the read/write process is blocked.
    *   Select has a limit on the number of open file descriptors, the default is 1024 (2048 for x64), 1 million concurrent, 1000 processes will be used, and the switching overhead is large; poll uses the linked list structure, and there is no limit to the number.
    *   Select, poll "wake up" when iterating over the entire fd collection, and epoll "wake up" as long as the judgment is ready list is empty, through the callback mechanism to save a lot of CPU time; select, poll call every time To copy the fd set from the user state to the kernel state, epoll only needs to copy once.
    *   With the increase of concurrent poll, the performance gradually declines. Epoll adopts the red-black tree structure and has stable performance. It will not decrease as the number of connections increases.
*   ["select, poll, epoll comparison"](http://xingyunbaijunwei.blog.163.com/blog/static/76538067201241685556302/)

    *   In situations where the number of connections is small and the connections are very active, the performance of select and poll may be better than epoll. After all, the epoll notification mechanism requires a lot of function callbacks.
*   ["In-depth understanding of Java NIO"](https://www.cnblogs.com/geason/p/5774096.html)

    *   NIO is a synchronous non-blocking IO model.</font> <font style="vertical-align: inherit;">Synchronization means that the thread continuously polls for IO events. Non-blocking means that the thread can wait for IO and can do other tasks at the same time.
*   ["The difference between BIO and NIO, AIO"](https://blog.csdn.net/skiof007/article/details/52873421)

*   ["Two Efficient Server Design Models: Reactor and Proactor Models"](https://blog.csdn.net/u013074465/article/details/46276967)

### Epoll

*   ["epoll use detailed (essential)"](https://www.cnblogs.com/fnlingnzb-learner/p/5835573.html)

### Java NIO

*   ["In-depth understanding of Java NIO"](https://www.cnblogs.com/geason/p/5774096.html)
*   ["An example of a Java NIO writing Socket server"](https://blog.csdn.net/xidianliuy/article/details/51612676)

### Kqueue

*   [Kqueue usage introduction](http://www.cnblogs.com/luminocean/p/5631336.html)

## Connections and short connections

*   ["TCP/IP Series - Difference between Long and Short Connections"](https://www.cnblogs.com/pangguoping/p/5571422.html)

## frame

*   ["Netty principle analysis"](https://blog.csdn.net/excellentyuxiao/article/details/53390408)
    *   Reactor mode introduction.
    *   Netty is an implementation of Reactor mode.

## Zero-copy

*   [Understanding of Zero Copy for Netty ByteBuf](https://www.cnblogs.com/xys1228/p/6088805.html)
    *   Multiple physically separate buffers are logically merged into one, thus avoiding data copying between memory.

## 

### Hessian

*   ["Hessian Principle Analysis"](https://www.cnblogs.com/happyday56/p/4268249.html)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">Binary-RPC; not just serialization

### Protobuf

*   ["Java application example of Protobuf protocol"](https://blog.csdn.net/antgan/article/details/52103966)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">Goolge produced, occupied space and efficiency outperformed other serialization libraries such as Hessian; need to write .proto file.

*   ["Protocol Buffers Serialization Protocol and Application"](https://worktile.com/tech/share/prototol-buffers)

    *   Explain about the agreement; Disadvantages: poor readability;
*   ["Simple use of protobuf and protostuff"](https://blog.csdn.net/eric520zenobia/article/details/53766571)

    *   The advantage of protostuff is that instead of writing .proto files, Java objects can be serialized directly.

# database

## Basic theory

### Three paradigms of database design

*   ["Three Paradigms of Database and Five Constraints"](https://www.cnblogs.com/waj6511988/p/7027127.html)
    *   The first normal form: each column (each field) in the data table must be the smallest unit that cannot be split, that is, to ensure the atomicity of each column;
    *   Second Normal Form (2NF): After satisfying 1NF, all the columns in the table must be dependent on the primary key. No column can be related to the primary key. That is, a table describes only one thing.
    *   The third paradigm: must meet the second paradigm (2NF), requirements: each column in the table is only directly related to the primary key and not indirectly, (each column in the table can only rely on the primary key);

## MySQL

### principle

*   ["InnoDB indexing principle of MySQL"](http://www.admin10000.com/document/5372.html)

*   ["MySQL Storage Engine - Difference between MyISAM and InnoDB"](https://blog.csdn.net/xifeijian/article/details/20316775)

    *   The main difference between the two types is that Innodb supports transaction processing and foreign key and row-level locking
*   ["The difference between myisam and innodb index implementation"](https://www.2cto.com/database/201211/172380.html)

### InnoDB

*   ["An article with you read Mysql and InnoDB"](https://my.oschina.net/kailuncen/blog/1504217)

### optimization

*   [MySQL36 Rules](http://vdisk.weibo.com/s/muWOT)

*   ["The best 20+ experience of MYSQL performance optimization"](https://www.cnblogs.com/zhouyusheng/p/8038224.html)

*   ["SQL Optimization"](https://blog.csdn.net/when_less_is_more/article/details/70187459)

*   ["The cause of the mysql database deadlock and the solution"](https://www.cnblogs.com/sivkun/p/7518540.html)

*   ["Possibility of causing index failure"](https://blog.csdn.net/monkey_d_feilong/article/details/52291556)

*   ["MYSQL paging limit speed is too slow optimization method"](https://blog.csdn.net/zy_281870667/article/details/51604540)

    *   In principle, it is to narrow the scanning range.

### index

#### Clustered index, non-clustered index

*   ["MySQL Clustered Index/Non-Clustered Indexes"](https://blog.csdn.net/no_endless/article/details/77073549)
*   ["MyISAM and InnoDB Index Implementation"](https://www.cnblogs.com/zlcxbb/p/5757245.html)

MyISAM is non-clustered, InnoDB is aggregated

#### Composite index

*   ["Comprehensive Index Advantages and Precautions"](https://www.cnblogs.com/summer0space/p/7247778.html)

#### 

*   [InnoDB Storage Engine - Adaptive Hash Index](https://blog.csdn.net/Linux_ever/article/details/62043708)

### Explain

*   ["MySQL Performance Optimizer Explain Use Analysis"](https://segmentfault.com/a/1190000008131735)

## NoSQL

### MongoDB

*   [MongoDB Tutorial](http://www.runoob.com/mongodb/mongodb-tutorial.html)
*   ["The Advantages and Disadvantages of Mongodb vs. Relational Databases"](http://mxdxm.iteye.com/blog/2093603)
    *   Advantages: weak consistency (eventually consistent), better guarantee user access speed; built-in GridFS, support for large-capacity storage; Schema-less database, no pre-defined structure; built-in Sharding; compared to other NoSQL, third-party support is rich Superior performance;
    *   Disadvantages: mongodb does not support transaction operations; mongodb takes up too much space; MongoDB does not have mature maintenance tools such as MySQL, which is a noteworthy area for development and IT operations;

### Hbase

*   ["Concise HBase Primer (Opening)"](http://www.thebigdata.cn/HBase/35831.html)

*   ["In-depth study of the principle of HBase architecture"](https://www.cnblogs.com/qiaoyihang/p/6246424.html)

*   ["The difference between traditional row storage and (HBase) column storage"](https://blog.csdn.net/youzhouliu/article/details/67632882)

*   ["The difference between Hbase and traditional database"](https://blog.csdn.net/lifuxiangcaohui/article/details/39891099)

    *   Empty data is not stored, saving space and is suitable for concurrency.
*   [HBase Rowkey Design](https://blog.csdn.net/u014091123/article/details/73163088)

    *   Rowkey is arranged in lexicographic order for batch scanning.
    *   Hot spots can be avoided by hashing.

# search engine

## Search Engine Principle

*   ["Inverted Index - Search Engine Getting Started"](https://www.jianshu.com/p/0193dc44135b)

## Lucene

*   ["Introduction to Lucene"](https://www.cnblogs.com/rodge-run/p/6551152.html)

## Elasticsearch

*   ["Elasticsearch learning, please look at this one!</font> <font style="vertical-align: inherit;">》](https://blog.csdn.net/laoyang360/article/details/52244917)
*   [Elasticsearch Index Theory](https://blog.csdn.net/cyony/article/details/65437708)

## Solr

*   ["Apache Solr Tutorial"](https://blog.csdn.net/u011936655/article/details/51960005)
*   [Comparison between "elasticsearch and solr"](https://blog.csdn.net/convict_eva/article/details/53537837)

## Sphinx

*   ["Sphinx's Introduction and Theory Exploration"](http://blog.jobbole.com/101672/)

# performance

## Performance Optimization Methodology

*   ["15-day performance optimization work, 5 aspects of tuning experience"](https://blog.csdn.net/huangwenyi1010/article/details/72673447?ref=myread)

    *   Code level, business level, database level, server level, front-end optimization.
*   ["Several Aspects of System Performance Optimization"](https://blog.csdn.net/tenglizhe/article/details/44563135)

## Capacity assessment

*   ["Methodology and Typical Cases for Network Performance and Capacity Assessment"](https://blog.csdn.net/u012528360/article/details/70054156)
*   ["Internet architecture, how to design capacity?</font> <font style="vertical-align: inherit;">》](https://mp.weixin.qq.com/s?__biz=MjM5ODYxMDA5OQ==&mid=2651959542&idx=1&sn=2494bbea9a855e0e1c3ccd6d2562a600&scene=21#wechat_redirect)
    *   Assess total visits, evaluate average visits QPS, evaluate peak QPS, evaluate systems, stand-alone limit QPS

## CDN network

*   ["CDN Acceleration Principle"](https://www.cnblogs.com/wxiaona/p/5867685.html)
*   [What are the better CDNs in China?</font> <font style="vertical-align: inherit;">》](https://www.zhihu.com/question/20536932)

## connection pool

*   ["Mainstream Java Database Connection Pool Comparison and Development Configuration Actual Battle"](https://blog.csdn.net/fysuccess/article/details/66972554)

## Performance tuning

*   [Nine Java performance debugging tools, at least one](https://blog.csdn.net/yethyeth/article/details/73266455)

# Big Data

## Flow calculation

### Storm

*   [Official website](http://storm.apache.org/)
*   [The most detailed Storm tutorial](https://blog.csdn.net/uisoul/article/details/77989927)

### Flink

*   ["Flink One Flink Basic Principles Introduction"](https://blog.csdn.net/lisi1129/article/details/54844919)

### Kafka Stream

*   [Kafka Stream Research: A Lightweight Flow Computing Model](https://yq.aliyun.com/articles/58382)

### Application scenario

E.g:

*   Advertising related real-time statistics;
*   Recommended system user image tag updates in real time;
*   Online service health monitoring in real time;
*   Real-time rankings;
*   Real-time statistics.

## Hadoop

*   ["What is Hadoop, what can I do in easy-to-understand words?"](https://blog.csdn.net/houbin0912/article/details/72967178)
*   ["The most detailed Hadoop environment in history"](http://gitbook.cn/books/5954c9600326c7705af8a92a/index.html)

### HDFS

*   ["[Hadoop Learning] HDFS Basic Principles"](https://segmentfault.com/a/1190000011575458)

### MapReduce

*   ["Introducing Map/Reduce Principles in Plain English"](https://blog.csdn.net/oppo62258801/article/details/72884633)
*   ["Simple map-reduce java example"](https://blog.csdn.net/foye12/article/details/78358292)

### Yarn

*   ["Preliminary Mastery of Yarn's Architecture and Principles"](http://www.cnblogs.com/codeOfLife/p/5492740.html)

## Spark

*   ["Spark (1): Basic Architecture and Principles"](http://www.cnblogs.com/tgzhu/p/5818374.html)

# Safety

## Web security

### XSS

*   ["xss Attack Principles and Solutions"](https://blog.csdn.net/qq_21956483/article/details/54377947)

### CSRF

*   ["CSRF Principles and Prevention"](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/641-web-an-quan-fang-fan/6412-csrf.html)

### SQL injection

*   [SQL Injection](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/641-web-an-quan-fang-fan/6413-sql-zhu-ru.html)

### Hash Dos

*   ["Evil JAVA HASH DOS Attack"](http://www.freebuf.com/articles/web/14199.html)
    *   Using JsonObjet to upload large Json, JsonObject uses HashMap at the bottom; different data produces the same hash value, making the build Hash slower and running out of CPU.
*   [An Advanced DoS Attack - Hash Collision Attack](https://yq.aliyun.com/articles/92194?t=t1)
*   ["About Hash Collision DoS: Parsing and Solution"](http://www.iteye.com/news/23939/)

### Script injection

*   ["The principle and prevention of the vulnerability of uploading files"](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/641-web-an-quan-fang-fan/6414-shang-chuan-wen-jian-guo-lv.html)

### Vulnerability Scan Tool

*   ["DVWA"](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/6421-dvwa.html)
*   [W3af](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/w3af.html)
*   [Detailed OpenVAS](https://blog.csdn.net/xygg0801/article/details/53610640)

### Verification code

*   ["Verification Code Principle Analysis and Implementation"](https://blog.csdn.net/niaonao/article/details/51112686)

*   ["Detailed Explanation of the Implementation Principle of Slip Authentication Code"](https://my.oschina.net/jiangbianwanghai/blog/1031031)

    *   The sliding verification code evaluates the risk based on the response time, drag speed, time, position, trajectory, number of retries, etc. of the user in the sliding slider.
*   [Taobao sliding verification code research](https://www.cnblogs.com/xcj26/p/5242758.html)

## DDoS protection

*   ["Learning Guide: DDoS Attacks and Defenses"](http://netsecurity.51cto.com/art/201601/503799.htm)
*   ["Free DDoS Attack Test Tool Collection"](http://netsecurity.51cto.com/art/201406/442756.htm)

## User privacy protection

1.  User password is not stored in plain text, plus dynamic slat.
2.  ID number, mobile number If you want to display, replace some of the characters with "*".
3.  The display of the contact information is controlled by the user himself or herself.
4.  TODO

*   [What does "Personal Privacy include?"](https://zhidao.baidu.com/question/1988017976673661587.html)

*   ["On the Internet, what is the scope of privacy?</font> <font style="vertical-align: inherit;">》](https://www.zhihu.com/question/20137108)

*   ["User password save"](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/642-shu-ju-jia-mi/6425-jia-mi-chang-jing-ff1a-yong-hu-mi-ma-bao-cun.html)

## Serialization vulnerability

*   ["Lib's past?</font> <font style="vertical-align: inherit;">Java Universal Deserialization Vulnerability Analysis](https://blog.chaitin.cn/2015-11-11_java_unserialize_rce/)

## encrypt and decode

### Symmetric encryption

*   [Common symmetric encryption algorithm](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/642-shu-ju-jia-mi/6421-chang-jian-dui-cheng-jia-mi-suan-fa.html)
    *   DES, 3DES, Blowfish, AES
    *   DES uses a 56-bit key and Blowfish uses 1- to 448-bit variable keys, AES 128, 192, and 256-bit length keys.
    *   The DES key is too short (56-bit only) algorithm is currently replaced by AES, and AES has hardware acceleration and performs well.

### Hash algorithm

*   [Commonly used hash algorithm](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/642-shu-ju-jia-mi/6422-chang-jian-ha-xi-suan-fa-and-hmac.html)

    *   MD5 and SHA-1 are no longer secure and have been deprecated.
    *   Currently SHA-256 is relatively safe.
*   [Public Internet URL Signature Verification Design Scheme Based on Hash Digest Signature](https://blog.csdn.net/zhangruhong168/article/details/78033202)

### Asymmetric encryption

*   [Common Asymmetric Encryption Algorithm](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/642-shu-ju-jia-mi/6424-chang-yong-fei-dui-cheng-jia-mi-suan-fa.html)
    *   RSA, DSA, ECDSA (Helix Curve Encryption Algorithm)

    *   Unlike RSA, DSA can only be used for digital signatures and cannot encrypt or decrypt data. Its security is comparable to that of RSA, but its performance is faster than that of RSA.

    *   The 256-bit ECC key has the same security as the 3072-bit RSA key.

        [Blockchain encryption technology](http://baijiahao.baidu.com/s?id=1578348858092033763&wfr=spider&for=pc)

## Server security

*   [Linux Enforcement: 15 Steps to Build a Secure Linux Server](http://www.freebuf.com/articles/system/121540.html)

## Data Security

### data backup

TODO

## Network isolation

### Internal and external network separation

TODO

### Login board

In the internal and external environment, log in to the online host through the springboard.

*   ["Build a simple bastion machine"](http://blog.51cto.com/zero01/2062618)

## Authorization, certification

### RBAC

*   ["Permission Design Based on Role of Organization"](https://www.cnblogs.com/zq8024/p/5003050.html)
*   ["Permission System and RBAC Model Overview"](https://www.cnblogs.com/shijiaqi1066/p/3793894.html)
*   ["Spring integrates Shiro to do a detailed case analysis of permission control module"](https://blog.csdn.net/he90227/article/details/38663553)

### OAuth2.0

*   [Understanding OAuth 2.0](http://www.ruanyifeng.com/blog/2014/05/oauth_2_0.html)

### 

2FA - Two-factor authentication for enhanced login authentication

Common practice is login password + phone verification code (or token key, similar to the USB key with online banking)

*   ["Two-Factor Authentication (2FA) Tutorial"] (</font> </font>[http://www.ruanyifeng.com/blog/2017/11/2fa-tutorial.html](http://www.ruanyifeng.com/blog/2017/11/2fa-tutorial.html)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">)

### 

*   [Single Sign-On Principle and Simple Implementation](https://www.cnblogs.com/ywlaker/p/6113927.html)

*   [CAS single sign-on framework](https://github.com/apereo/cas)

# Common open source framework

## Open Source Agreement

*   ["Open Source Agreement Selection"](https://coderxing.gitbooks.io/architecture-evolution/chapter1/di-yi-zhang-ff1a-zhun-bei-qi-cheng/12-guan-yu-kai-yuan/123-kai-yuan-xie-yi-de-xuan-ze.html)

*   [How to choose an open source software agreement](http://choosealicense.online/)

## Logging framework

### Log4j, Log4j2

*   ["log4j explain in detail"](https://blog.csdn.net/u012422446/article/details/51199724)
*   ["log4j2 practical use Detailed Explanation"](https://blog.csdn.net/vbirdbest/article/details/71751835)
*   ["Log4j1, Logback and Log4j2 performance test comparison"](https://my.oschina.net/OutOfMemory/blog/789267)
    *   Log4J asynchronous log performance is excellent.

### Logback

*   ["The most comprehensive LogBack detailed, with java case and configuration instructions"](https://blog.csdn.net/rulon147/article/details/52620541)

## ORM

*   [ORM Framework Uses Advantages and Disadvantages](https://blog.csdn.net/sinat_34093604/article/details/53082000)
    *   The main purpose is to improve the development efficiency.

**MyBatis:**

*   ["Mybatis caching mechanism explain"](https://www.cnblogs.com/winclpt/articles/7511672.html)

    *   The first level cache is the SqlSession level cache, the cached data only valid in the SqlSession
    *   The second-level cache is the mapper-level cache, which is shared by the same namespace, so the SqlSession is shared; the cache is cleared using the LRU mechanism, and is enabled by the cacheEnabled parameter.
*   ["MyBatis Learning Code Generator Generator"](https://blog.csdn.net/baidu_32877851/article/details/53959268)

## Network framework

TODO

## Web framework

### Spring family

**Spring**

*   [Spring Concise Tutorial](https://www.w3cschool.cn/wkspring/)

**Spring Boot**

*   [Official website](http://projects.spring.io/spring-boot/)
*   [Spring Boot Basic Tutorial](http://blog.didispace.com/Spring-Boot%E5%9F%BA%E7%A1%80%E6%95%99%E7%A8%8B/)

**Spring Cloud**

*   [Spring Boot Chinese Index Station](http://springboot.fun/)
*   [Spring Cloud Chinese Documentation](https://springcloud.cc/)
*   [Spring Cloud Basic Tutorial](http://blog.didispace.com/Spring-Cloud%E5%9F%BA%E7%A1%80%E6%95%99%E7%A8%8B/)

## Tool frame

*   ["Introduction and Simple Use of Apache Commons Tools"](https://www.cnblogs.com/crazylqy/p/4872236.html)
*   [Google guava Chinese Course](http://ifeve.com/google-guava/)

# Distributed design

## Scalable design

*   [Ten Top Ten Scalable Architectures that Architects Must Know](https://blog.csdn.net/hemin1003/article/details/53633926)

    *   In summary, the common routine is distribution, caching, and asynchronous processing.
*   ["Scalability Design Data Segmentation"](https://yq.aliyun.com/articles/38119)

    *   Horizontal splitting + vertical splitting
    *   Use middleware for sharding such as MySQL Proxy.
    *   Segmentation is performed using a sharding strategy, such as modulo the ID.
*   ["Talk about how to implement scalable large-scale website architecture"](https://blog.csdn.net/deniro_li/article/details/78458306)

    *   Distributed Services + Message Queuing.
*   ["Large Web Site Technology Architecture (7)--Website Extensibility Framework"](https://blog.csdn.net/chaofanwei/article/details/29191073)

## Stability & High Availability

*   ["System Design: Some Technical Solutions for High Availability Systems"](https://blog.csdn.net/hustspy1990/article/details/78008324)

    *   Scalable: horizontal expansion, vertical expansion.</font> <font style="vertical-align: inherit;">Through redundant deployment, single points of failure are avoided.
    *   Isolation: Avoiding a single business occupies all resources.</font> <font style="vertical-align: inherit;">Avoid business interactions 2\. Computer room isolation avoids single points of failure.
    *   Decoupling: Reduce maintenance costs and reduce coupling risks.</font> <font style="vertical-align: inherit;">Reduce dependence and reduce mutual influence.
    *   Current limiting: sliding window counting, leaky bucket algorithm, token bucket algorithm and other algorithms.</font> <font style="vertical-align: inherit;">When encountering burst traffic, ensure the system is stable.
    *   Degradation: The release of non-core functional resources in an emergency.</font> <font style="vertical-align: inherit;">Sacrifice non-core business to ensure high availability of core business.
    *   Fuse: An abnormal condition exceeds the threshold and enters the blown state and quickly fails.</font> <font style="vertical-align: inherit;">Reduce the impact of unstable external dependencies on core services.
    *   Automated testing: Reduce faults caused by publications through comprehensive testing.
    *   Grayscale publishing: Grayscale publishing is a compromise between speed and security that can effectively reduce release failures.
*   ["About Highly Available Systems"](https://coolshell.cn/articles/17459.html)

    *   Design principles: data is not lost (persistent); service is highly available (copy of service); absolute 100% high availability is difficult, the goal is to do as much as 9, such as 99.999% (accrued for only 5 minutes throughout the year).

### Hardware load balancing

*   ["turn!</font> <font style="vertical-align: inherit;">!</font> <font style="vertical-align: inherit;">Comparison of the advantages and disadvantages of the load balancer technology Nginx and F5](https://www.cnblogs.com/wuyun-blog/p/6186198.html)

    *   Mainly compared with F5.
*   [How much do you know about software/hardware load balancing products?</font> <font style="vertical-align: inherit;">》](https://www.cnblogs.com/lcword/p/5773296.html)

### Software load balancing

*   ["Several load balancing algorithms"](https://www.cnblogs.com/tianzhiliang/articles/2317808.html)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">round robin, weight, load, least connection, QoS

*   [DNS Load Balancing](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/611-dns-fang-shi.html)

    *   The configuration is simple and the update speed is slow.
*   [Nginx Load Balancing](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/613-nginx-fu-zai-jun-heng.html)

    *   Simple and lightweight, low learning cost; mainly suitable for web applications.
*   ["Load balancing with LVS+Keepalived"](https://www.cnblogs.com/edisonchou/p/4281978.html)

    *   The configuration comparison load only supports up to four layers and the performance is high.
*   ["HAProxy usage details of the entire network of the most detailed Chinese document"](http://www.ttlsa.com/linux/haproxy-study-tutorial/)

    *   Support to seven layers (such as HTTP), more comprehensive features, performance is not bad.
*   ["Haproxy + Keepalived + MySQL to achieve read-balance load"](http://blog.itpub.net/25704976/viewspace-1319781/)

    *   Mainly load balancing of user read requests.
*   ["rabbitmq+haproxy+keepalived achieve high availability cluster construction"](https://www.cnblogs.com/lylife/p/5584019.html)

### Limiting

*   ["Talk about the Current Limitations of High Concurrent Systems"](https://www.cnblogs.com/haoxinyue/p/6792309.html)
    *   Counter: Sliding the window counter to control the number of requests per unit time, simple and crude.
    *   Leaky bucket algorithm: Fixed-capacity leaky buckets, which are frequently used when the leaky bucket is full.
    *   Token bucket algorithm: a fixed-capacity token bucket. To add a token at a certain rate, the token needs to be obtained before the request is processed. If the token is not available, the request is discarded or the queue is dropped. The rate of adding the token can be controlled. To control the overall speed.</font> <font style="vertical-align: inherit;">The RateLimiter in Guava is an implementation of a token bucket.
    *   Nginx limiting: By</font> </font>`limit_req`limiting the number of concurrent connections module.

### Application layer disaster recovery

*   ["Avalanche Fighters: Principles and Uses of Fused Hystrix"](https://segmentfault.com/a/1190000005988895)

    *   Avalanche effect causes: hardware failures, hardware failures, program bugs, retries to increase traffic, and user requests.
    *   Avalanche countermeasures: current limit, improved cache mode (cache preload, synchronous call change asynchronous), automatic expansion, and degraded.
    *   Hystrix Design Principles:
        *   Resource isolation: Hystrix avoids service avalanche by isolating each dependent service by assigning separate thread pools for resource isolation.
        *   Fuse switch: health status of service = request failures / total number of requests, threshold setting and sliding window control switch.
        *   Command mode: wraps the service invocation logic by inheriting the HystrixCommand.
*   [Cache Penetration, Cache Breakdown, Cache Avalanche Solution Analysis](https://blog.csdn.net/zeb_perfect/article/details/54135506)

*   ["Cache Breakdown, Failure, and Hot Key Problems"](https://blog.csdn.net/zeb_perfect/article/details/54135506)

    *   The main strategy: failure instant: stand-alone use of locks; use of distributed lock; not expire;
    *   Hotspot data: Hotspot data is stored separately; use local cache; divided into multiple subkeys;

### Cross-room disaster recovery

*   ["Distribution Experience of Multi-Room and Multi-Rooms"](http://dc.idcquan.com/ywgl/71559.shtml)

    *   Synchronous data synchronization through self-developed middleware.
*   ["Disposal of living in different places (remote living) experience"](https://blog.csdn.net/jeffreynicole/article/details/48135093)

    *   Pay attention to the delay problem. Multiple calls across the room will amplify the delay several times.
    *   There is a large probability that there will be a large number of building room lines, and fault tolerance will be done at the operation and maintenance level and at the program level.
    *   Can not rely on dual-write data in the program, there must be automatic synchronization program.
    *   The data never considers high delays or poor network quality, considering synchronization quality issues.
    *   The core business and the secondary business are divided and conquered, and even only the core business is considered.
    *   Remote live monitoring deployment and testing should also keep up.
    *   Consider user partitions where business is allowed, especially games and email services.
    *   Control the size of the message body across the room, the smaller the better.
    *   Consider using docker container virtualization technology to improve dynamic scheduling capabilities.
*   [Disaster recovery technology and construction experience](https://blog.csdn.net/yoara/article/details/38013751)

### Disaster recovery drill process

*   ["Reliance Governance, Grayscale Distribution, Fault Exercises, Design and Practical Experience of Alibaba.com's Fault Exercise System"](https://mp.weixin.qq.com/s?__biz=MjM5MDE0Mjc4MA==&mid=2650996320&idx=1&sn=0ed3be190bbee4a9277886ef88cbb2e5)
    *   Common fault portrait
    *   Case: Preplan validity, plan validity, fault replication, architecture disaster recovery testing, parameter tuning, parameter tuning, fault raid, and joint drill.

### Smooth start

*   Smooth restart application ideas 1\. End-point traffic (such as vip layer), 2\. Flush data (if any), 3, restart the application

*   ["The JVM security exit (how to gracefully shut down the java service)"](https://blog.csdn.net/u011001084/article/details/73480432)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">Recommended to introduce: System.exit, Kill SIGTERM; not recommended kill-9; use Runtime.addShutdownHook registration hook.

*   ["How Common Java Applications](http://ju.outofmemory.cn/entry/337235)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">Are</font> [<font style="vertical-align: inherit;">Gracefully Closed"</font>](http://ju.outofmemory.cn/entry/337235) <font style="vertical-align: inherit;">Java, Srping, Dubbo gracefully closes.

## Database expansion

### Read-write separation mode

*   ["Implementation of Mysql master-slave scheme"](https://www.cnblogs.com/houdj/p/6563771.html)

*   ["Build MySQL Master-Slave Replication Classic Architecture"](https://www.cnblogs.com/edisonchou/p/4133148.html)

*   ["Haproxy+ Load Balancing with Multiple MySQL Slave Servers"](https://blog.csdn.net/nimasike/article/details/48048341)

*   [DRBD+Heartbeat+Mysql High Availability Read/Write Detach Architecture](https://www.cnblogs.com/zhangsubai/p/6801764.html)

    *   DRDB performs disk copying to avoid single points of problems.
*   ["MySQL Cluster Method"](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/62-ke-kuo-zhan-de-shu-ju-ku-jia-gou/621-gao-ke-yong-mysql-de-ji-zhong-fang-an/6214-mysql-cluster-fang-an.html)

### Fragmentation mode

*   ["Sub-tables need to consider the issues and programs"](https://www.jianshu.com/p/32b3e91aa22c)

    *   Middleware: Lightweight: sharding-jdbc, TSharding; Heavyweight: Atlas, MyCAT, Vitess, etc.
    *   Problem: transaction, Join, migration, expansion, ID, paging, etc.
    *   Transaction compensation: reconciliation of data; comparison based on logs; regular synchronization with standard data sources.
    *   Sub-library strategy: numerical range; modulus; date, etc.
    *   The number of sub-libraries: usually MySQL single library 50 million, Oracle single library 100 million need to sub-library.
*   ["MySql Table and Table Partition Detailed"](https://www.2cto.com/database/201503/380348.html)

    *   Partitioning: It is an internal mechanism of MySQL. It is transparent to the client. Data is stored in different files. On the surface, it is the same table.
    *   Table: Physically create different tables, clients need to manage the sub-table routing.

## Service governance

### Service Registration and Discovery

*   ["Never lose contact!</font> <font style="vertical-align: inherit;">How to achieve service discovery in microservice architecture?</font> <font style="vertical-align: inherit;">》](https://blog.csdn.net/jiaolongdy/article/details/51188798)

    *   Client service discovery mode: The client directly queries the registry and is responsible for load balancing.</font> <font style="vertical-align: inherit;">Eureka uses this approach.
    *   Server-side service discovery mode: The client queries service instances through load balancing.
*   ["SpringCloud Service Registry Comparison: Consul vs Zookeeper vs Etcd vs Eureka"](https://blog.csdn.net/u010963948/article/details/71730165)

    *   CAP support: Consul (CA), zookeeper (cp), etcd (cp), Euerka (ap)
    *   The author thinks Consul's support for Spring cloud is better.
*   ["Zookeeper based service registration and discovery"](http://mobile.51cto.com/news-502394.htm)

    *   Advantages: API is simple, Pinterest, Airbnb in use, multi-language, through the watcher mechanism to achieve configuration PUSH, can quickly respond to configuration changes.

### Service Routing Control

*   [Distributed Services Framework Study Notes 4 Service Routing](https://blog.csdn.net/xundh/article/details/59492750)
    *   Principle: Transparent routing
    *   Load Balancing Policy: Random, Polling, Service Call Latency, Consistent Hash, Sticky Connection
    *   Local routing has a limited strategy: injvm (preferentially calling jvm internal services) and initial (priority using the same physical machine services), and in principle finding the nearest service.
    *   Configuration method: unified registry, local configuration, and dynamic delivery.

## Distributed consensus

### CAP and BASE theory

*   ["Discussing CAP Theory, BASE Theory from Distributed Consistency"](http://www.cnblogs.com/szlbm/p/5588543.html)
    *   Consistency classification: strong agreement (immediately consistent); weakly consistent (achievable in units of time, such as seconds); eventually consistent (weakly consistent, eventually consistent within a certain period of time)
    *   CAP: Consistency, Availability, Partition Fault Tolerance (Cause of Network Failure)
    *   BASE: Basically Available, Soft state, and Eventually consistent
    *   The core idea of ​​BASE theory is: Even if it can not achieve strong consistency, but each application can be based on their own business characteristics, using appropriate methods to achieve the final consistency of the system.

### Distributed lock

*   ["Several Implementations of Distributed Locks"](http://www.hollischuang.com/archives/1716)

    *   Database-based distributed locks: Advantages: Simple and easy to understand.</font> <font style="vertical-align: inherit;">Disadvantages: There is a single point problem, the database can be a large overhead, not reentrant;
    *   Cache-based distributed locks: Advantages: Non-blocking, good performance.</font> <font style="vertical-align: inherit;">Disadvantages: Operation is not easy to cause the lock can not be released.
    *   Zookeeper distributed lock: The lock mechanism is implemented by an orderly temporary node, and its corresponding node needs to be the smallest, and it is considered that the lock is obtained.</font> <font style="vertical-align: inherit;">Advantages: The cluster can solve single problems transparently, avoiding locks from being released, and locks can be reentrant.</font> <font style="vertical-align: inherit;">Disadvantages: Performance is not as good as caching, and throughput decreases as the zk cluster grows in size.
*   ["Zookeeper Based Distributed Lock"](https://www.tuicool.com/articles/VZJr6fY)

    *   Clear principle description + Java code example.
*   ["jedisLock-redis distributed lock implementation"](https://www.cnblogs.com/0201zcr/p/5942748.html)

    *   Based on setnx(set if ont exists), it returns false, otherwise it returns true.</font> <font style="vertical-align: inherit;">And support expired time.
*   [Memcached and Redis Distributed Locking Scheme](https://blog.csdn.net/albertfly/article/details/77412333)

    *   Use the add (as opposed to set) operation of memcached to return false when the key exists.

### Distributed consensus algorithm

#### PAXOS

*   ["Distributed Series Articles - Principles and Derivation of Paxos Algorithm"](https://www.cnblogs.com/linbingdong/p/6253479.html)
*   [Paxos-->Fast Paxos-->Zookeeper Analysis](https://blog.csdn.net/u010039929/article/details/70171672)
*   ["Distributed" Zookeeper and Paxos](https://www.cnblogs.com/leesf456/p/6012777.html)

#### Zab

*   ["Introduction to Distributed Coherence Protocols in Zab:Zookeeper"](https://www.jianshu.com/p/fb527a64deee)

#### Raft

*   [Why is Raft More Easier to Understand Distributed Consistency Algorithms?](http://www.cnblogs.com/mindwind/p/5231986.html)
    *   Three roles: Leader, Follower, Candidate
    *   The ballot was sent out by way of random waiting, winning more votes.

#### Gossip

*   [Gossip algorithm](http://blog.51cto.com/tianya23/530743)

#### Two-phase commit, multi-phase commit

*   ["About Distributed Transactions, Two-Phase Commit Protocol, Third-Order Commit Protocol"](http://blog.jobbole.com/95632/)

### Idempotent

*   ["Distributed Systems - Idempotency Design"](https://www.cnblogs.com/wxgblogs/p/6639272.html)
    *   The role of idempotency: The resource is idempotent and the requester doesn't need to worry about repeated calls that can generate errors.
    *   Common means to guarantee idempotency: MVCC (similar to optimistic locking), deduplication table (unique index), pessimistic locking, one-time token, serial number mode.

### Distributed consensus solution

*   [Distributed System Transactional Conformance Solution](http://www.infoq.com/cn/articles/solution-of-distributed-system-transaction-consistency)
*   ["Six Plans to Guarantee the Consistency of Distributed System Data"](https://weibo.com/ttarticle/p/show?id=2309403965965003062676)

### Distributed Leader node election

*   ["Using zookeeper for distributed leader node elections"](https://blog.csdn.net/johnson_moon/article/details/78809995)

###  Flexible Transactions

*   ["Traditional and Flexible Affairs"](https://www.jianshu.com/p/ab1a1c6b08a1)
    *   Based on BASE theory: basic availability, flexibility, and eventual consistency.
    *   Solution: Record log + compensation (forward supplement or rollback), message retry (requires the program to be exponentiated, etc.); "no lock design", using optimistic locking mechanism.

## Distributed File System

*   [Talk about distributed file storage system - basic architecture](https://zhuanlan.zhihu.com/p/27666295)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">?
*   ["Compare the distributed file system"](https://blog.csdn.net/gatieme/article/details/44982961)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">?
    *   HDFS: Read and write large amounts of data for high-throughput scenarios, not for small files.
    *   FastDFS: lightweight, suitable for small files.

## Unique ID generation

### Globally unique ID

*   [Generating Globally Unique Id Summary in Highly Concurrent Distributed Systems](https://www.cnblogs.com/baiwa/p/5318432.html)

    *   Twitter scheme (Snowflake algorithm): 41-bit timestamp + 10-digit machine identifier (such as IP, server name, etc.) + 12-digit serial number (local counter)
    *   Flicker project: MySQL self-increment ID + "REPLACE INTO XXX:SELECT LAST_INSERT_ID();"
    *   UUID: Disadvantages, unordered, too long strings, take up space, affect retrieval performance.
    *   MongoDB Scenario: Use ObjectId.</font> <font style="vertical-align: inherit;">Disadvantages: can not increase.
*   [The TDDL SEQUENCE Principle Under Distributed](https://blog.csdn.net/hdu09075340/article/details/79103851)

    *   Create a sequence table in the database to record the maximum value of the id that is currently occupied.
    *   Each client host takes an id interval (such as 1000~2000) cached locally, and updates the id maximum record in the sequence table.
    *   Different id ranges are used between client hosts. After they are used up and fetched, optimistic locking is used to control concurrency.

## Consistent hashing algorithm

*   [The consistent hash algorithm](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/631-yi-zhi-xing-ha-xi.html)

# Design Ideas & Development Models

## 

*   ["Talking about my understanding of DDD-driven design"](https://www.cnblogs.com/netfocus/p/5548025.html)

    *   Concept: DDD is mainly proposed for the separation of the various stages of the traditional software development process (Analysis-Design-Code) to avoid undeliverable software (and requirements) due to unclear analysis at first or inconsistent information flow during software development. Assuming inconsistencies).</font> <font style="vertical-align: inherit;">DDD emphasizes that everything is centered on the domain and emphasizes the role of Domain Expert. It emphasizes that the domain model is first defined and then developed, and the domain model can guide the development (the so-called driver).
    *   Process: Understanding the domain, splitting the domain, refining the domain, the accuracy of the model depends on the depth of understanding of the model.
    *   Design: DDD proposes modeling tools such as aggregations, entities, value objects, factories, warehousing, domain services, and domain events to help with domain modeling.
*   ["Summary of Domain Driven Design Basics"](https://www.cnblogs.com/butterfly100/p/7827870.html)

    *   Domain (Doamin) is essentially a problem domain, such as an e-commerce system, a forum system, etc.
    *   Bounded Context: Explains the relationship between subdomains and can be simply understood as a subsystem or component module.
    *   Domain Model: The core of DDD is to establish the correct domain model (using universal description language, tools, and domain common language); to reflect the nature of business requirements, including entities and processes; it runs through software analysis, design, and development. Process; commonly used expression field model: diagram, code or text;
    *   Domain common language: Domain experts, developers and designers can have immediate language or tools.
    *   The classic layered architecture: user interface/presentation layer, application layer, domain layer, and infrastructure layer is a four-tier architecture model.
    *   The mode used:
        *   Link as little as possible, as far as possible single item, try to reduce the overall complexity.
        *   Entity: The only indication in the domain that an entity has as few attributes as possible and at least as clear.
        *   Value Object: There is no unique identifier, and the property value is immutable. The second is a simple object, such as Date.
        *   Domain Service: Coordinate multiple domain objects, only the method has no state (no data); it can be divided into application layer services, domain layer services, and basic layer services.
        *   Aggregate, Aggregate Root: Aggregate defines a set of related objects with a cohesive relationship; the aggregate root is the only element of the aggregate reference; when modifying an aggregate, it must be at the transaction level; most areas In the model, 70% of aggregates usually have only one entity, and 30% only have 2 to 3 entities; if an aggregate has only one entity, then this entity is the aggregate root; if there are multiple entities, then we can think about which object in the aggregate Has independent significance and can interact with the outside directly;
        *   Factory: Similar to the factory mode in design mode.
        *   Repository: Persisting to DB, managing objects, and designing storage only for aggregates.
*   ["Realm Driven Design (DDD) Road to Realization"](http://www.cnblogs.com/Leo_wl/p/3866629.html)

    *   Aggregation: For example, a Car contains components such as Engine, Wheel, and Tank.
*   ["Field-Driven Design Series (2) Analysis of VO, DTO, DO, PO Concepts, Differences, and Uses"](http://www.hollischuang.com/archives/553)

### 

CQRS - Command Query Responsibility Seperation

*   ["Field Driven Design Series (6): CQRS"](https://www.cnblogs.com/cnblogsfans/p/4551990.html)

    *   The core idea: read and write separation (inquiry and update in different methods), different processes are only different design methods, CQ code separation, there will be obvious manifestation in the distributed environment (in the case of redundant data), the purpose is For high performance.
*   ["Comparison of advantages and disadvantages of DDD CQRS architecture and traditional architecture"](http://www.techweb.com.cn/network/system/2017-07-07/2553563.shtml)

    *   Ultimately consistent design concept; depends on highly available message middleware.
*   ["Introduction to CQRS Architecture"](http://www.cnblogs.com/netfocus/p/4055346.html)

    *   An abstract case of implementing CQRS.
*   [Depths: My Thoughts on CQRS/EventSourcing Architecture](http://www.uml.org.cn/zjjs/201609221.asp)

    *   CQRS Pattern Analysis + 12306 Ticket Picking Cases

### Anemia, congestive model

*   ["Anemia, explanation of hyperemia model, and some experience"](https://kb.cnblogs.com/page/520743/)
    *   Blood loss model: Lao Tzu and son are defined separately, and they do not know each other. There is no business logic in the entity definition of the two, and they are related through external services.
    *   Anemia model: Laozi knows son, son also knows Laozi; part of the business logic is put into the entity; Advantages: Individual layers of dependent, structural clear, easy to maintain; Disadvantages: does not meet the OO thinking, compared to the congestion model, the service layer is more heavy ;
    *   Congestion model: Similar to the anemia model, the difference lies in how to divide the business logic.</font> <font style="vertical-align: inherit;">Advantages: The service layer is relatively thin, only acts as a facade, does not deal with DAO, compound OO thinking; disadvantages: non-single dependency, bi-directional dependency between DO and DAO, and logical division of the Service layer is likely to cause confusion.
    *   Swollen mode: It is an extreme situation, cancel the service layer, all the business logic in DO; Advantages: in line with OO ideas, simplification of layering; Disadvantages: too much exposure information, many non-DO logic will be forced into DO.</font> <font style="vertical-align: inherit;">This pattern should be avoided.
    *   The authors advocate using the anemia model.

## Actor mode

TODO

## Reactive programming

### Reactor

TODO

### RxJava

TODO

### Vert.x

TODO

## DODAF2.0

*   ["DODAF2.0 Methodology"](http://www.360doc.com/content/16/0627/19/33945750_571201779.shtml)
*   [How DodiF2.0's Capability Perspective Goes?](http://blog.51cto.com/xiaoyong/1553164)

## Serverless

TODO

## Service Mesh

TODO

*   [What is Service Mesh?</font> <font style="vertical-align: inherit;">》](https://time.geekbang.org/article/2355)

# Project management

## Architecture review

*   ["How architecture design reviews architecture design specifications"](http://developer.51cto.com/art/201506/478486.htm)
*   ["Everyone is an architect: Non-functional requirements"](https://blog.csdn.net/wireless_com/article/details/45935591)

## Reconstruction

*   ["Reconstruction of the 12 Military Rules"](http://www.infoq.com/cn/articles/architect-12-rules-complete/)

## Code specification

TODO

## Code Review

Institution or system! In addition, each company needs to develop its own check list based on its own needs and goals.

*   ["Why did you do bad Code Review?</font> <font style="vertical-align: inherit;">》](http://www.sohu.com/a/229745352_181657)

    *   The code review does well in institutional building.
*   ["From scratch Code Review"](https://blog.csdn.net/uxyheaven/article/details/49773619)

*   [Code Review Checklist](https://www.cnblogs.com/zuoping/p/5477047.html)

*   ["Java Code Review Checklist"](https://dzone.com/articles/java-code-review-checklist)

*   ["How to use gitlab for code review"](https://blog.csdn.net/legend0011/article/details/45585575)

## RUP

*   ["Using RUP 4+1 View Method for Software Architecture Design"](https://blog.csdn.net/apanious/article/details/51011946)

## Kanban Management

*   ["Talk about the Application of Kanban in Projects"](https://blog.csdn.net/tkchen/article/details/51637643)

## SCRUM

SCRUM - Scrimmage

*   Three roles: Product Owner (PO) Product Owner; Scrum Master (SM) to promote Scrum execution; Team development team.

*   3 artifacts: Product Backlog product TODOLIST, with priority; Sprint Backlog function development TODO LIST; burn down diagram;

*   Five Values: Focus, Courage, Openness, Commitment, Respect.

*   ["Agile project management process - Scrum framework is the most complete!</font> <font style="vertical-align: inherit;">》](https://blog.csdn.net/inny100_100/article/details/54633757)

*   ["Agile is actually very simple 3 - scrum agile method"](https://blog.csdn.net/superkunkun/article/details/52951142)

## Agile development

TODO

## 

XP - eXtreme Programming

*   ["Mainstream Agile Development Method: Extreme Programming XP"](http://www.woshipm.com/pmd/406917.html)
    *   It is a methodology to guide developers.

    *   4 great values:

        *   Communication: Encourage verbal communication and increase efficiency.
        *   Simple: Just enough.
        *   Feedback: timely feedback, notify relevant people.
        *   Courage: Advocate embrace change, dare to reconstruct.
    *   Five principles: fast feedback, simple assumptions, gradual modification, promotion of change (small step run), high quality work (guarantee the quality of the premise to guarantee small steps run).

    *   5 jobs: Staged sprints; sprint planning meetings; daily standing meetings; sprint review;

## Pair programming

Write code, edge review.</font> <font style="vertical-align: inherit;">Can enhance code quality and reduce bugs.

*   [Pair Programming](http://www.baike.com/wiki/%E7%BB%93%E5%AF%B9%E7%BC%96%E7%A8%8B)

## FMEA management model

TODO

# General Business Terms

TODO

# Technical trends

TODO

# Policies and regulations

TODO

## legal

### Strictly abide by Article 253 of the Criminal Law

Article 253 of the Chinese Criminal Law states:

> *   Staff of state agencies or units in finance, telecommunications, transportation, education, medical care, etc., who, in violation of state regulations, sell or illegally provide personal information of citizens obtained by the entity in the course of performing its duties or providing services to others, if the circumstances are serious, Departments shall be sentenced to fixed-term imprisonment of not more than 3 years or criminal detention and shall be concurrently executed or a single fine.
> *   If the above information is stolen or otherwise illegally obtained, and the circumstances are serious, it shall be punished in accordance with the provisions of the preceding paragraph.
> *   If a unit guilty of the first two crimes, the unit shall be fined, and the person directly in charge and other persons directly responsible shall be punished in accordance with the provisions of each paragraph.

The Supreme People's Court and the Supreme People's Procuratorate's Supplementary Provisions (IV) on the enforcement of the "Criminal Law of the People's Republic of China" confirming that the offender violates paragraph 1 of Article 253 of the Criminal Law and constitutes the crime of "selling and illegally providing personal information of citizens"; Infringe the provisions of paragraph 2 of Article 253 of the Criminal Law and constitute the crime of “illegal acquisition of personal information of citizens”

*   ["Illegal Acquisition of Personal Information of Citizens"](https://baike.baidu.com/item/%E9%9D%9E%E6%B3%95%E8%8E%B7%E5%8F%96%E5%85%AC%E6%B0%91%E4%B8%AA%E4%BA%BA%E4%BF%A1%E6%81%AF%E7%BD%AA)

# Architect quality

*   [Architect Portrait](http://hellojava.info/?p=430)

    *   Business understanding and abstraction capabilities
    *   NB's code capabilities
    *   Comprehensiveness: 1\. Will there be multiple technical solutions in the minds of architects in the face of business problems; 2\. Do you consider enough aspects in the design of the system? 3\. Do you consider enough in system design? Many aspects;
    *   Global: Whether to consider the impact on the upstream and downstream systems.
    *   Tradeoffs: trade-offs between input-output ratios; priority and rhythm control;
*   [What Things Architects Must Know About Architecture Optimization and Design](http://www.infoq.com/cn/articles/architecture-optimization-and-design-the-architect-must-know)

    *   The details to consider: Modular, light-coupled, shared-nothing architecture; reduction of dependencies before individual components, attention to dependencies between services, and all the resulting chain failures and effects.
    *   Comprehensive consideration of infrastructure, configuration, testing, development, operation and maintenance.
    *   Consider the influence of people, teams, and organizations.
*   ["How can I really improve myself and become an outstanding architect?</font> <font style="vertical-align: inherit;">》](https://www.zhihu.com/question/19841397)

*   ["Architect's Essential Quality and Growth Path"](https://blog.csdn.net/sanbingyutuoniao123/article/details/54144129)

    *   Quality: business understanding, breadth of technology, depth of technology, rich experience, communication skills, hands-on capabilities, and aesthetic qualities.
    *   Growth path: 2 years of accumulated knowledge, 4 years of accumulated skills and influence within the group, 7 years of accumulated influence within the sector, and 7 years of accumulated cross-sectoral influence.
*   ["Architects - Where are you on the floor?</font> <font style="vertical-align: inherit;">》](http://blog.51cto.com/frankfan/1248401)

    *   The first-tier architect sees only the product itself
    *   The second-tier architect not only saw his own product but also saw the overall solution
    *   Third-tier architects see business value

# Team management

TODO

## Recruitment

# Information

## Industry information

*   [36kr](http://36kr.com/)
*   [Techweb](http://www.techweb.com.cn/)

## Public number list

TODO

## Blog

### Team blog

*   [Ali Middleware Blog](http://jm.taobao.org/)
*   [US Mission Review Technology Team Blog](https://tech.meituan.com)

### personal blog

*   [Shan Yifeng's Weblog](http://www.ruanyifeng.com/)
*   [Cool Shell - COOLSHELL-Chen Hao](https://coolshell.cn/)
*   [Hellojava - Ali Bixuan](http://hellojava.info/)
*   [Cm's Blog](http://cmsblogs.com/)
*   [Program 猿 DD - Yongchao Chao - Author of Spring Cloud Microservices Act](http://blog.didispace.com/)

## Integrated portal, community

**domestic:**

*   [CSDN](http://csdn.net)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">veteran technology community, do not have to explain.

*   [51cto.com](http://www.51cto.com/)

*   [ITeye](http://www.iteye.com/)

    *   Partial Java direction
*   [Blog Park](https://www.cnblogs.com)

*   [ChinaUnix](http://www.tom.net/)

    *   Partial Linux direction
*   [Open source Chinese community](https://www.oschina.net/)

*   [Deep open source](http://www.open-open.com/)

*   [Bole Online](http://www.jobbole.com/)

    *   Covers IT workplace, Web front end, back end, mobile end, database and other aspects, partial technology.
*   [ITPUB](http://www.itpub.net/)

*   [Tencent Cloud - Cloud + Community](https://cloud.tencent.com/developer/column)

*   [Alibaba Cloud - Yunqi Community](https://yq.aliyun.com/)

*   [IBM DeveloperWorks](https://www.ibm.com/developerworks/cn/)

*   [Developer headlines](https://toutiao.io/)

*   [LinkedKeeper](http://www.linkedkeeper.com)

**foreign:**

*   [DZone](https://dzone.com)
*   [Reddit](https://www.reddit.com)

## Q&A, discussion community

*   [Segmentfault](https://segmentfault.com)
    *   Q&A + Column
*   [Know almost](https://www.zhihu.com/)
*   [Stackoverflow](https://stackoverflow.com/)

## Industry data analysis

*   [Ereli Net](http://report.iresearch.cn/)

*   [QUEST MOBILE](https://www.questmobile.com.cn)

*   [National data](http://data.stats.gov.cn/)

## Special website

*   test:

    *   [Pilot Testing International](http://www.ltesting.net/)
    *   [Test nest](https://www.testwo.com/)
    *   [TesterHome](https://testerhome.com)
*   Operation and maintenance:

    *   [Operation and maintenance](http://www.yunweipai.com/)
    *   [Abcdocker](https://www.abcdocker.com/)
*   Java:

    *   [ImportNew](http://www.importnew.com/)
        *   Focus on Java technology sharing
    *   [HowToDoInJava](https://howtodoinjava.com/)
        *   English blog
*   Safety

    *   [Red and Black Alliance](https://www.2cto.com/)
    *   [FreeBuf](http://www.freebuf.com/)
*   Big Data

    *   [China Big Data](http://www.thebigdata.cn/)
*   Other special websites:

    *   [DockerInfo](http://www.dockerinfo.net/)
        *   Website focused on Docker applications and consulting, tutorials.
    *   [Linux Commune](https://www.linuxidc.com/)
        *   Linux Theme Community

## other

*   [Programmer skills map](https://github.com/TeamStuQ/skill-map)

## Recommended reference book

### Online eBooks

*   ["Understanding Spring Cloud and Microservice Construction"](https://github.com/forezp/SpringCloudLearning)

*   ["Ali Technical Reference Atlas - R&D"](http://techforum-img.cn-hangzhou.oss-pub.aliyun-inc.com/1523849261680/AliTech101_RD.pdf)

*   ["Ali Technical Reference Atlas - Algorithm"](http://techforum-img.cn-hangzhou.oss-pub.aliyun-inc.com/1523848064814/AliTech101_Algorithms.pdf)

*   ["2018 US Mission Review Technology New Year (Collection)" 70M](http://dpurl.cn/n/1lqcX)

*   [InfoQ "Architects" Monthly](http://www.infoq.com/cn/architect/)

*   [The Road to Architects](https://www.w3cschool.cn/architectroad/)

### Paper book

#### Development aspects

*   "Alibaba Java Development Handbook"</font> </font>[Jingdong</font> </font>](https://union-click.jd.com/jdc?d=bVKwZQ)[Taobao](https://s.taobao.com/search?q=%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4Java%E5%BC%80%E5%8F%91%E6%89%8B%E5%86%8C)

#### Architecture aspects

*   "Software Architect's 12 Practices: Technical Skills"</font> </font>[Jingdong</font> </font>](https://union-click.jd.com/jdc?d=gXvRd8)[Taobao](https://s.taobao.com/search?q=%E8%BD%AF%E4%BB%B6%E6%9E%B6%E6%9E%84%E5%B8%88%E7%9A%8412%E9%A1%B9%E4%BF%AE%E7%82%BC%EF%BC%9A%E6%8A%80%E6%9C%AF%E6%8A%80%E8%83%BD%E7%AF%87)
*   "The Beauty of Architecture"</font> </font>[Jingdong</font> </font>](https://union-click.jd.com/jdc?d=xJit5I)[Taobao](https://s.taobao.com/search?q=%E6%9E%B6%E6%9E%84%E4%B9%8B%E7%BE%8E)
*   "Distributed Service Architecture"</font> </font>[Jingdong</font> </font>](https://union-click.jd.com/jdc?d=JS5Od9)[Taobao](https://s.taobao.com/search?q=%E5%88%86%E5%B8%83%E5%BC%8F%E6%9C%8D%E5%8A%A1%E6%9E%B6%E6%9E%84)
*   "Talking Architecture"</font> </font>[Jingdong</font> </font>](https://union-click.jd.com/jdc?d=FHooH4)[Taobao](https://s.taobao.com/search?q=%E8%81%8A%E8%81%8A%E6%9E%B6%E6%9E%84)
*   "Cloud native application architecture practice"</font> </font>[Jingdong</font> </font>](https://union-click.jd.com/jdc?d=orkJSj)[Taobao](https://s.taobao.com/search?q=%E4%BA%91%E5%8E%9F%E7%94%9F%E5%BA%94%E7%94%A8%E6%9E%B6%E6%9E%84%E5%AE%9E%E8%B7%B5)
*   "100 million-level traffic site architecture core technology"</font> </font>[Jingdong</font> </font>](https://union-click.jd.com/jdc?d=RnOSP5)[Taobao](https://s.taobao.com/search?q=%E4%BA%BF%E7%BA%A7%E6%B5%81%E9%87%8F%E7%BD%91%E7%AB%99%E6%9E%B6%E6%9E%84%E6%A0%B8%E5%BF%83%E6%8A%80%E6%9C%AF)
*   "This decade of Taobao technology"</font> </font>[Jingdong</font> </font>](https://union-click.jd.com/jdc?d=LwrDfD)[Taobao](https://s.taobao.com/search?q=%E6%B7%98%E5%AE%9D%E6%8A%80%E6%9C%AF%E8%BF%99%E5%8D%81%E5%B9%B4)
*   "Transformation of Enterprise IT Architecture - Strategic Thinking of China-Taiwan Strategy and Architecture Combat"</font> </font>[Jingdong</font> </font>](https://union-click.jd.com/jdc?d=89pAEm)[Taobao](https://s.taobao.com/search?q=%E4%BC%81%E4%B8%9AIT%E6%9E%B6%E6%9E%84%E8%BD%AC%E5%9E%8B%E4%B9%8B%E9%81%93)

#### Technical management

*   "CTO said"</font> </font>[Jingdong</font> </font>](https://union-click.jd.com/jdc?d=zhTZyr)[Taobao](https://s.taobao.com/search?q=CTO%E8%AF%B4)
*   "Technology Management"</font> </font>[Jingdong</font> </font>](https://union-click.jd.com/jdc?d=LgRBUW)[Taobao](https://s.taobao.com/search?q=%E6%8A%80%E6%9C%AF%E7%AE%A1%E7%90%86%E4%B9%8B%E5%B7%85)
*   "Netease Arabian Nights: The Reality of Internet Product Project Management"</font> </font>[Jingdong</font> </font>](https://union-click.jd.com/jdc?d=jcRz2r)[Taobao](https://s.taobao.com/search?q=%E7%BD%91%E6%98%93%E4%B8%80%E5%8D%83%E9%9B%B6%E4%B8%80%E5%A4%9C%EF%BC%9A%E4%BA%92%E8%81%94%E7%BD%91%E4%BA%A7%E5%93%81%E9%A1%B9%E7%9B%AE%E7%AE%A1%E7%90%86%E5%AE%9E%E6%88%98)

#### Basic theory

*   The beauty of mathematics</font> </font>[Jingdong</font> </font>](https://union-click.jd.com/jdc?d=ghIES2)[Taobao](https://s.taobao.com/search?q=%E6%95%B0%E5%AD%A6%E4%B9%8B%E7%BE%8E)
*   "Programming Beads"</font> </font>[Jingdong</font> </font>](https://union-click.jd.com/jdc?d=YmhdEu)[Taobao](https://s.taobao.com/search?q=%E7%BC%96%E7%A8%8B%E7%8F%A0%E7%8E%91)

#### Tools

TODO

#### Big data

# Technical resources

## Open source resources

*   [Github](https://github.com)

*   [Apache Software Foundation](https://www.apache.org/index.html)

## Manuals, Documents, Tutorials

**domestic:**

*   [W3Cschool](http://w3cschool.cn)

*   [Runoob.com](http://www.runoob.com/)

    *   HTML, CSS, XML, Java, Python, PHP, design patterns, and other introductory manuals.
*   [Love2.io](https://love2.io/)

    *   Many, many Chinese online e-books are a new open source technology document sharing platform.
*   [Gitbook.cn](http://gitbook.cn/)

    *   Paid e-books.
*   [ApacheCN](http://www.apachecn.org/)

    *   AI, big data series Chinese documents.

**foreign:**

*   [Quick Code](http://www.quickcode.co/)
    *   Free online technical tutorials.
*   [Gitbook.com](http://gitbook.com)
    *   There are some Chinese e-books.
*   [Cheatography](https://www.cheatography.com/)
    *   Cheat Sheets, a one-page document website.
*   [Tutorialspoint](https://www.tutorialspoint.com/index.htm)
    *   Well-known tutorial website, providing high-quality introductory tutorials such as Java, Python, JS, SQL, big data.

## Online class

*   [Apprentice worry-free](http://www.xuetuwuyou.com/)
*   [Geek time](https://time.geekbang.org/)
*   [Segmentfault](https://segmentfault.com/lives)
*   [Stark College](https://new.stuq.org/course/explore)
*   [Niu Ke Network](http://nowcoder.com)
*   [Geek College](https://www.jikexueyuan.com/)
*   [51CTO College](http://edu.51cto.com/)

## conference

*   [QCon](http://www.infoq.com/cn/qcon/)
*   [ArchSummit](https://archsummit.com)
*   [GITC Global Internet Technology Conference](http://www.thegitc.com/)

**Event publishing platform:**

*   [Activity line](http://www.huodongxing.com/)

## Common APP

*   [Geek time](https://time.geekbang.org)
*   [get](https://www.igetget.com)

## find a job

*   [Boss Direct Employment](https://www.zhipin.com)
*   [Pulling the net](https://www.lagou.com)
*   [Hunting](https://www.liepin.com)
*   [100Offer](https://cn.100offer.com/)

## tool

*   [Geek Search](https://s.geekbang.org/)
    *   Technical article search engine.

## Code hosting

*   [Coding](https://coding.net)
*   [Code cloud](https://gitee.com/)

## File service

*   Seven cattle
*   Shooting clouds again

## Comprehensive cloud service provider

*   Ali Cloud
*   Tencent Cloud
*   Baidu cloud
*   Sina Cloud
*   Jinshan Yun
*   [Amazon Cloud (AWS)](https://amazonaws-china.com/cn/)
*   [Google Cloud](https://cloud.google.com/?hl=zh-cn)
*   [Microsoft Cloud](https://azure.microsoft.com/zh-cn/)

### VPS

*   [Linode](http://linode.com)
