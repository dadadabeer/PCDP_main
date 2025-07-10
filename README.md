🧵 Parallel, Concurrent, and Distributed Programming — Coursework Archive

📝 Summary
This repository contains all code and reports written during my Parallel, Concurrent, and Distributed Programming course (Aug 2024 – Dec 2024). It includes both theoretical assignments and programming tasks that explore key abstractions, challenges, and tools in concurrent and distributed computing.

Topics covered include:

Functional vs Imperative Programming in Scala

Thread Safety and Mutual Exclusion

Locking Mechanisms: Spinlocks, Semaphores, Monitors

Concurrent Data Structures: Queues, Stacks, Skiplists

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
Designed and implemented a custom Hybrid Sort (merge + insertion) that was benchmarked to be ~3× faster than Scala’s built-in Array.sort on randomized datasets. This exercise focused on thread pool implementation and fine-grained parallelism. (Report available in the Repository : PCDP_Mid_Term_Report (2).pdf)


🔹 Final Project – Distributed Key-Value Store
Built a fault-tolerant, replicated key-value store using techniques in distributed consensus, message passing, and failure handling. The project required designing a fully asynchronous architecture capable of recovering from node crashes and message loss. (Report available in the Repository : PCDP_FINAL_KV_STORE (4).pdf

🔹 Open Source Race Condition Analysis – Chronicle Map
As part of a mini research project, I analyzed the Chronicle Map open-source codebase for potential race conditions using Facebook Infer and manual auditing. I proposed several fixes for unsafe access patterns, improper synchronization, and inconsistent visibility, all of which were documented with reproducible examples and formal justifications. (Report available in the Repository : ChronicleMap_Research_Project (1).pdf)

🤚🏻 Ownership
All files in this repository were authored by me except the Chronicle-Map and unless otherwise noted via @author.

