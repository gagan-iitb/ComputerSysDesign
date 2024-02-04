# Course Page for CS559 (Computer Systems Design)

To be taught at IIT Bhilai, India in the Winter Semester of 2024. 

__Course Instructor:__ [Dr. Gagan Raj Gupta ](https://www.iitbhilai.ac.in/index.php?pid=gagan) 

Real-life applications are complex and involve a variety of components (multiple clients, backend servers, databases, ML modules, all connected by a network). We want our applications to be intelligent, adaptive (data-driven), scalable, reliable, and performant. How do we go from the idea to the design to its implementation and successful operationalization?

This course attempts to teach the basic principles underlying system design, implementation, and evaluation of computer systems. It provides an introduction to the fundamentals of analytic modeling techniques that are used in computer system design. Students will also learn general systems concepts that support design goals of modularity, performance, and security. Students will apply materials learned in lectures and readings to design, build and evaluate new systems components.

__Objectives:__

After completing this class, the students will be able to design their own distributed systems to solve real-world problems. The ability to design one's own distributed system includes an ability to argue for one's design choices.

The students will be able to evaluate and critique existing systems and their own system designs. As part of that, students will learn to recognize design choices made in existing systems.

__Learning Outcomes:__

The students will be able to apply the technical material taught in the lecture to new system components. This implies an ability to recognize and describe:

• How common design patterns in computer systems—such as abstraction and modularity are used to limit complexity.

• How operating systems use virtualization and abstraction to enforce modularity.

• How reliable, usable distributed systems can be built on top of an unreliable network.

• How to measure system performance and what can we do to improve performance and scalability?

__Pre-requisites__

Undergraduate course in Computer Networks and Operating Systems 

__All the assignments will assume familiarity with cloud services such as AWS. Familiarity with it is a pre-requisite__
The following courses may be helpful to you:
* __https://explore.skillbuilder.aws/learn/course/external/view/elearning/11458/aws-cloud-quest-cloud-practitioner__
* __https://www.coursera.org/learn/aws-cloud-practitioner-essentials__
* __https://aws.amazon.com/getting-started/hands-on__


__Class Timings and Location__

Lecture Room: L102
Lecture Timings: 8:30 a.m. to 9:30 a.m. On Mondays and 9:30 am -10:30 am on Wednesdays and Friday

__Course Materials__

* Google Drive Link with Lecture materials for IIT Bhilai Students: [GDrive](https://drive.google.com/drive/folders/1i0VtvMyIu4FIVmAxFJ81NnOdoT1atasW)

* Canvas Link for registered Students (for Assignments and Discussions): [Canvas](https://canvas.instructure.com/courses/4085885)

__Textbook/Reference books:__
1. [SJK] Saltzer, Jerome H. and M. Frans Kaashoek. 2009, Principles of Computer System Design: An Introduction, Part I. Morgan Kaufmann, ISBN: 9780123749574. Part II
of the textbook is available on MIT OpenCourseWare.

2. [MB] Mor Harchol-Balter, February 2013, Performance Modeling and Design of Computer Systems: Queueing Theory in Action, Cambridge University Press

3. [BL] Butler Lampson, 2011, Hints and Principles for Computer Systems Design,
(https://arxiv.org/ftp/arxiv/papers/2011/2011.02455.pdf )

4. [LZGS] E. D. Lazowska, J. Zahorjan, G. S. Graham, K. C. Sevcik, 1984, Quantitative System Performance, Prentice Hall.

5. [LK] L. Kleinrock, 1975. Queueing Systems Volume I: Theory, Wiley Interscience. 
6. [OSTEP](https://pages.cs.wisc.edu/~remzi/OSTEP/) Remzi H. Arpaci-Dusseau and Andrea C. Arpaci-Dusseau, Operating Systems: Three Easy Pieces, Arpaci-Dusseau Books, 2018
7. Alex Xu's books: **https://bytebytego.com/**
8. [UDS] https://understandingdistributed.systems/ : Simplified and easy to follow description of essential concepts on a wide range of topics
9. Google SRE books: https://sre.google/books/
10. 

__Grading Plan__

* 2 Exams: 50%
* Weekly System Design Exercise (In class): 15% [will mimic system design interviews]
* 1 Assignment: 10%
* 1 Project: 25% [Project will include a mock interview]

The assignment is individual. The project will be end-to-end (full stack) in a team. Students are encouraged to build balanced teams [front-end developer, back-end developer, ML engineer, tester, architect roles] 

__Detailed Schedule__

* __Week1__: Introduction to the course, modularity, building a Campus Service Application, Building Blocks of AWS (reading assignment)
* __Week2__: Building Reliable and Secure Communications, Networks, API Design 
* __Week3__: Design for Maintainability: testing, tracing, logging, metrics
* __Week4__: System Design Interview Preparation, High-Level Design, Back of Envelope Calculations, Detailed Design
* __Week5__: System Scalability and performance analysis basics
* __Feb5-9__: Rate Limiter, Open and Closed Systems, Process Coordination, Concurrency
        * https://blog.bytebytego.com/p/rate-limiter-for-the-real-world
        * https://builtin.com/software-engineering-perspectives/rate-limiter


* __Week7__: Distributed Systems (Case study)
* __Week8__: Reliable storage and File Systems
* __Exam Week__: No classes
* __Research Papers__: After exam 1, we will switch gears and study both classical and recent papers on 3 main topics: Caching, DBs, ML Systems.

__Similar courses available in other institute(s) / MOOC portals:__

* MIT 6.033: Computer Systems Engineering (http://web.mit.edu/6.033/www/ )

* Princeton COS 316: Principles of Computer Systems Design
(https://www.cs.princeton.edu/courses/archive/fall19/cos316/ )

* University of Wisconsin Madison, CS547: Computer Systems Modeling Fundamentals
(http://pages.cs.wisc.edu/~vernon/cs547/cs547.html )

* CMU 15-857: Analytical Performance Modeling & Design of Computer Systems
(https://www.cs.cmu.edu/~harchol/Perfclass/class21fall.html )

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
