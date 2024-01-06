# 6.5840: Distributed Systems Engineering - Lecture 1: Introduction

## Definition of a Distributed System

- A group of computers cooperating to provide a service.
- Focus on infrastructure services like storage for big websites, MapReduce, and peer-to-peer sharing.

## Why Build Distributed Systems?

- Increase capacity through parallel processing.
- Tolerate faults via replication.
- Match distribution of physical devices, e.g., sensors.
- Increase security through isolation.

## Challenges

- Concurrency, complex interactions, partial failure, and achieving high performance.

## Importance of Study

- Hard problems with powerful solutions.
- Wide usage in big Web sites.
- Active research area with significant unsolved problems.
- Building these systems is challenging and part of the course labs.

## Course Structure

- **Lecturers:** Frans Kaashoek and Robert Morris
- **Teaching Assistants:** Upamanyu Sharma, Yun-Sheng Chang, Daniel Wisdom
- Components: Lectures, papers, two exams, labs, and an optional final project.
- Lectures will cover big ideas, paper discussions, and lab guidance.
- Papers: Research papers (classic and new) assigned almost every lecture.
- Exams: Mid-term and final, focusing on papers and labs.
- Labs: To deepen understanding of key ideas and distributed programming.
- Final Project: Optional, substitutes Lab 4, involves a group project with a demo.

## Main Topics

- Focus on infrastructure for applications (Storage, Communication, Computation).
- Goal: Hide complexity of distribution from applications.
- Topics: Fault tolerance, consistency, performance, and tradeoffs.
- Labs cover practical aspects like RPC, threads, and concurrency control.

## Case Study: MapReduce

- Overview: Simplifies multi-hour computations on large datasets.
- Abstract View: E.g., Word count using Map and Reduce functions.
- Scalability and hiding of details like load balancing and failure recovery.
- Limits on application capabilities (no real-time processing, iteration).
- Details on GFS (Google File System), Coordinator role, and performance limits.
- Fault tolerance strategies, handling of failures and worker crashes.

## Conclusion

- MapReduce popularized big cluster computation.
- Good scalability and simplicity for programmers.
- Trade-offs in efficiency and flexibility.
- Predecessors to more advanced systems discussed later in the course.
