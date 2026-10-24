# Course Page for CS559 (Computer Systems Design)

Being taught at IIT Bhilai, India in the Monsoon Semester of 2026. 

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

* How to design and deploy ML systems?

__Pre-requisites__

Undergraduate course in Computer Networks and Operating Systems. Basic courses in data science and ML (DS250, DS200, CS550)


__Class Timings and Location__

Lecture Room: LH101
Lecture Timings: 2:30-3:30 pm on Monday, Wed and Fridays
Lab Timings: 3:30-5:30 pm on Fridays in LH101

__Course Materials__

* Google Drive Link with Lecture materials for IIT Bhilai Students: [GDrive](https://drive.google.com/drive/folders/1i0VtvMyIu4FIVmAxFJ81NnOdoT1atasW)

__Textbook/Reference books:__

1. [MB] Mor Harchol-Balter, February 2013, Performance Modeling and Design of Computer Systems: Queueing Theory in Action, Cambridge University Press
2. [UDS] Roberto Vitillo, Understanding Distributed Systems, https://understandingdistributed.systems/ : Simplified and easy-to-follow description of essential concepts on a wide range of topics
3. [EDSI] Ville Tuulos, Effective Data Science Infrastructure: How to Make Data Scientists Productive, Manning Publications.
4. [MLSys] Vijay Reddy, 2026, Introduction to ML systems, ML systems at Scale. https://mlsysbook.ai/
5. [PDS] Unmesh Joshi, 2023, Patterns of Distributed Systems. https://martinfowler.com/books/patterns-distributed.html
6. [VDB] N Borwankar, 2026, Vector Databases, https://github.com/nborwankar/VectorDatabaseBook

__Grading Plan__

* **Qualifying Test (1st class): Mandatory to pass in order to continue the course.**
* 2 Exams: 50%
* **Attendance and Systems Design Notebook: 20%** Mandatory to maintain a dedicated notebook for the course, where you will maintain lecture notes with date, solve the system design questions and homeworks assigned in the course. Instructor will check notebooks at regular intervals and give marks accordingly. Digital notes and solutions won't be considered.
* 1 Assignment + Lab exercises: 15%
* 1 Project: 15% [Project will include a mock interview]

The assignment is individual. The project will be end-to-end (full stack) in a team. Students are encouraged to build balanced teams [front-end developer, back-end developer, ML engineer, tester, architect roles] 

__Letter Grades__
Grades will be awarded on absolute marks.
A: 90+
A-: 85+
B: 80+
B-: 75+
C: 65+
C-: 55+
D: 45+
F< 45

__Detailed Schedule and Topics covered in class 2026__

* __Week1__: Introduction to the course, modularity, layering, naming, emergent properties, trade-offs. 
*  Lecture 1: We discussed how modularity decreased the effort to debug code, Debugging an unreachable website.
*  Lecture 2: Collision Avoidance in Wi-FI and TCP Congestion Control, and their interaction.
*  Assignment 1 on Water Harvesting design for a village using Satellite images.
*  High Level Design is due on August 10, must be made in your course notebook. 

__Detailed description of Assignment 1:__
We are developing an application for village management to plan the placement of ponds in their village.
This involves analyzing contour maps, marking potential regions such as govt land for digging ponds, estimating the catchment area, querying rainfall data, estimating pond depth to catch heavy rainfall and presenting the results to the user.

__RESEARCH PAPERS AND READINGS__
* DBMS Architecture: https://www.cs.cmu.edu/~15721-f25/papers/DBMS_Architecture.pdf

* Bigtable: A Distributed Storage System for Structured Data : https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf
  
* Clickhouse Paper: https://www.vldb.org/pvldb/vol17/p3731-schulze.pdf

* Lakehouse: https://www.cs.cmu.edu/~15721-f25/papers/Lakehouse.pdf

* Advanced Query processing in Lakehouse: https://www.cs.cmu.edu/~15721-f25/papers/AQP_in_Lakehouse.pdf

* Snowflake: https://www.cs.cmu.edu/~15721-f25/papers/Snowflake_Disaggregated.pdf

* BigLake: https://www.cs.cmu.edu/~15721-f25/papers/BigLake.pdf

* Dremel: https://www.cs.cmu.edu/~15721-f25/papers/Dremel.pdf

* Join Ordering: https://arxiv.org/pdf/2502.15181

* Query Optimizers: https://www.cs.cmu.edu/~15721-f25/papers/ML_QO_vs_AQP.pdf

* FINGER: Fast approx nearest neighbors: https://arxiv.org/abs/2206.11408

* Fast-Convergent Proximity Graphs for Approximate Nearest Neighbor Search: https://arxiv.org/abs/2510.05975
* Six Dimensions of benchmarking Time Series Database: https://arxiv.org/pdf/2608.01459
* Survey of Time Series DB: https://nora.nerc.ac.uk/id/eprint/527832/7/N527832CR.pdf

* CAP Twelve Years Later: https://sites.cs.ucsb.edu/~rich/class/cs293b-cloud/papers/brewer-cap.pdf
* Eventual consistency: https://sites.cs.ucsb.edu/~rich/class/cs293b-cloud/papers/bailis-calm.pdf
* Virtualization notes: https://sites.cs.ucsb.edu/~rich/class/cs293b-cloud/notes/Virtualization/virtualization.html

* Geospatial Indexing: https://h3geo.org/docs/   https://s2geometry.io/
https://redis.io/glossary/geospatial-indexing/

* 








____OLD STUFF__
* __Week2__: Building Reliable and Secure Communications, Networks, API Design 
* __Week3__: Design for Maintainability: testing, tracing, logging, metrics
* __Week4__: System Design Interview Preparation, High-Level Design, Back of Envelope Calculations, Detailed Design
* __Week5__: System Scalability and performance analysis basics, load balancing
* __Week6__: Workload Characterization, Rate Limiter (Case Study), Open and Closed Systems
 * __Week7__: Reliable storage and File Systems, Key Value Store (Case Study). 
* __Exam Week__: No classes
* __Week8__:  Distributed Systems Fundamentals: Process Coordination, Concurrency, Consistent Hashing, 
* __Research Papers__: After exam 1, we will focus on: Caching, DBs, Patterns of Distributed Systems
