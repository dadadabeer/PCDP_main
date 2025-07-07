🧵 Parallel, Concurrent, and Distributed Programming — Coursework Archive
📝 Summary
This repository contains all code and reports written during my Parallel, Concurrent, and Distributed Programming course (Aug 2024 – Dec 2024). It includes both theoretical assignments and programming tasks that explore key abstractions, challenges, and tools in concurrent and distributed computing.

Topics covered include:

Functional vs Imperative Programming in Scala

Thread Safety and Mutual Exclusion

Locking Mechanisms: Spinlocks, Semaphores, Monitors

Concurrent Data Structures: Queues, Stacks, Skiplists

Consensus in Shared Memory (e.g., Paxos)

Read-Modify-Write operations and atomicity

Futures and Promises in Java and Scala

Parallel Collections in Scala

Actor-based Concurrency and Supervision (Akka)

Data Race Detection techniques

Distributed, Fault-Tolerant Key-Value Stores

🛠 Tech Stack
Languages: Scala, Java

Frameworks/Libraries: Akka, Java Futures, Scala Futures, Java Concurrency Utilities

🔬 Coursework Highlights
🔹 Midterm Project – Hybrid Sort
Designed and implemented a custom Hybrid Sort that was benchmarked to be ~3x faster than Scala’s built-in Array.sort on randomized datasets. This exercise focused on thread pool implementation and fine-grained parallelism.

🔹 Final Project – Distributed Key-Value Store
Built a fault-tolerant, replicated key-value store using techniques in distributed consensus, message passing, and failure handling. The project required designing a fully asynchronous architecture capable of recovering from node crashes and message loss.

🤚🏻 Ownership
All files in this repository were authored by me unless otherwise noted via @author.

