__Course Page for CS559 (Computer Systems Design)__
To be taught at IIT Bhilai, India in the Winter Semester of 2022.
Course Instructor: Dr. Gagan Raj Gupta, Dr. Subhajit Sidhanta

Real life applications are complex and involve a variety of components (multiple clients, backend servers, databases, all connected by a network). We want our applications to be scalable, reliable and performant. How do we go from the idea to the design to its implementation and successful operationalization?

This course is an attempt to teach the basic principles underlying system design, implementation, and evaluation of computer systems. It provides an introduction to the state-of-the-art analytic modelling techniques that are used in computer system design. Students will also learn general systems concepts that support design goals of modularity, performance, and security. Students will apply materials learned in lectures and readings to design, build and evaluate new systems components.

__Objectives:__

After completing this class, the students will be able to design their own distributed systems to solve real-world problems. The ability to design one's own distributed system includes an ability to argue for one's design choices.

The students will be able to evaluate and critique existing systems, as well as their own system designs. As part of that, students will learn to recognize design choices made in existing systems.

__Learning Outcomes:__

The students will be able to apply the technical material taught in lecture to new system components. This implies an ability to recognize and describe:

• How common design patterns in computer system—such as abstraction and modularity are used to limit complexity.

• How operating systems use virtualization and abstraction to enforce modularity.

• How the Internet is designed to deal with scale, a diversity of applications, and competing economic interests.

• How reliable, usable distributed systems are able to be built on top of an unreliable network.

• Common pitfalls in the security of computer systems, and how to combat them.

• How to measure system performance and what can we do to improve performance and scalability?


__Course content:__

* Introduction to systems: Example Systems- Operating Systems-Distributed File Systems-Databases-Web Frameworks-Networks 
* Case Studies: Twitter, Uber
* Rules of Thumb: Common Mistakes, Systematic Approach, 
* Systems design intro: Setting goals for your system-Principles of good design; 
* Performance Vs Scalability; Latency vs Thruput; CAP Theorem (Availability vs Consistency); Cost 
* Modeling Fundamentals: Quantitative Systems Design-Queuing Systems-Fundamental Laws and Applications-Asymptotic Bounds
* Naming Schemes: Unix File System-Git-Network Naming
* DNS, API Gateways, Zookeeper
* Caching: CPU Caching-CDN Caching
* Why CDN? Why Caching? Eviction Policies, Redis Intro, Design problems on CDNs
* Resource Management: Scheduling-Load Balancing-TCP throughput Model
* Load Balancing: Algorithms, Reverse Proxy
* WebSockets, Microservices Architecture vs Monoliths, OAUTH 2.0, Design Problems
* Hashing, Consistent Hashing, 
* Indexing, Data Partitioning, Sharding, Replication, Data Modeling Questions,
* Push vs Pull systems, 
* Other Topics: Virtualization-Security and Access Control-Reliability Models

__Pre-requisites__

Undergraduate course in Computer Networks and Operating Systems 


__Detailed Schedule__
Legend:
 ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Theory
 ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Labs

|#| Week| Topics planned in this week | Text Book Reference |
| --- | ------------| ----------- | -------- |
|1| ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Dec27 | Introduction to Systems Design; Goals of Systems;<br/> Example Systems: Web, Hadoop/Spark    | |
|1| ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Dec 27 | Lab: Introduction to AWS: EC2, S3, DynamoDB, ELB, Kinesis | |
|2| ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Jan3 | Key components in building systems (e.g. AWS services); <br/>System Design Principles: Rules of Thumb, Common Pitfalls in Systems Design; Correctness/Consistency; <br/>Key Metrics: Throughput, Latency, Availability, Jitter/Lags| |
|2| ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Jan 3 | Case Studies: Architecture of Several Large Applications such as Google Maps, AirBnB, Uber,  DropBox | |
|3| ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Jan10| Operational Laws: Little's Law, response-time law, asymptotic bounds, modification analysis, performance metrics, open systems, closed systems||
|3| ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Jan 10| Lab: Simulations: time averages versus ensemble averages, generating random variables for simulation, Inspection Paradox.||
|3| ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Jan 10| Case Studies: Architecture of Several Large Applications such as Instagram, Messenger, Twitter, Web Crawler, Ticketing Engine ||
|4| ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Jan17| Scalability; Models of Distributed Systems: Failures, Attacks ||
|4| ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Jan 17| Lab: Failure Testing, Injecting failures in your application ||
|5| ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Jan24| System Design Patterns for Fault Tolerance and High Availability||
|5| ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Jan 24| Lab: System design patterns ||
|6| ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Jan31| Load Balancing; Time, Clocks, Ordering, Consensus  ||
|6| ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Jan 31| __Project: Building a Fault-Tolerant and Available Web Application __ ||
|6| Feb 3| __Tierce 1 Exam__||
|7| ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Feb7| Naming: DNS, API Gateways, Distributed File Systems, Zookeeper      ||
|7| ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Feb 7| Lab: NFS ||
|8| ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Feb14| Databases:  Relational, Key-Value, Document, Graph||
|8| ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Feb 14| Lab: No-SQL Databases||
|8| ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Feb 14| Case Studies: Databases, E-Commerce, Web-Farms, DBOS ||
|9| ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Feb21| Modeling Empirical Workloads: Pareto distributions, heavy-tailed distributions, understanding variability and tail behavior,<br/> Important results from Queueing Theory: M/M/1, M/M/k, M/G/1 analysis  ||
|9| ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Feb 21| Lab: Redis Database Intro,  | |
|10| ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Feb28| Management of Server Farms: capacity provisioning, dynamic power management, routing policies||
|10| ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Feb 28| Lab: Performance Testing   |    |
|11| ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Mar7| Resource Management: Scheduling-Load Balancing-TCP throughput Model,  <br/> Load Balancing: Algorithms, Reverse Proxy ; <br/> Hashing, Consistent Hashing, Indexing, Data Partitioning, Sharding, Replication, Data Modeling Questions||
|11| ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Mar 7| __Project: Making your application Scalable and High-Performance__| |
|12| ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Mar 12-20|__Mid Sem Break__||
|12| ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Mar 21| __Tierce 2 Exam__||
|13| ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Apr4 | WebSockets, Microservices Architecture vs Monoliths, OAUTH 2.0, Design Problems ||
|13|  ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Apr4| Lab: Designing applications ||
|14| ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Apr11| Caching, CDNs ||
|14| ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Apr 11| Lab: Design problems on CDNs ||
|14| ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Apr 11| Case Studies: Akamai  ||
|15| ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Apr18| Message Queues: Push vs Pull systems; Distributed Ledgers: BlockChain ||
|15| ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Apr 18 | Lab: Kafka, BitCoin  ||
|15| ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Apr25| Other Topics: Virtualization-Security and Access Control-Reliability Models | |
|16| ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Apr 25| Lab: Openstack,  ||
|17 |![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Apr 25 |__Major Project: Complete a major system design course project__  ||




__Textbook/Reference books:__
1. Saltzer, Jerome H. and M. Frans Kaashoek. 2009, Principles of Computer System Design: An Introduction, Part I. Morgan Kaufmann, ISBN: 9780123749574. Part II
of the textbook is available on MIT OpenCourseWare.

2. Butler Lampson, 2011, Hints and Principles for Computer Systems Design,
(https://arxiv.org/ftp/arxiv/papers/2011/2011.02455.pdf )

3. E. D. Lazowska, J. Zahorjan, G. S. Graham, K. C. Sevcik, 1984, Quantitative System Performance, Prentice Hall.

4. L. Kleinrock, 1975. Queueing Systems Volume I: Theory, Wiley Interscience. 5. Mor Harchol-Balter, February 2013, Performance Modeling and Design of Computer Systems: Queueing Theory in Action, Cambridge University Press




__Similar courses available in other institute(s) / MOOC portals:__

* MIT 6.033: Computer Systems Engineering (http://web.mit.edu/6.033/www/ )

* Princeton COS 316: Principles of Computer Systems Design
(https://www.cs.princeton.edu/courses/archive/fall19/cos316/ )

* University of Wisconsin Madison, CS547: Computer Systems Modeling Fundamentals
(http://pages.cs.wisc.edu/~vernon/cs547/cs547.html )

* CMU 15-857: Analytical Performance Modeling & Design of Computer Systems
(https://www.cs.cmu.edu/~harchol/Perfclass/class21fall.html )

