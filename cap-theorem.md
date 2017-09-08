The theorem states that **networked shared-data systems **can only guarantee/strongly support two of the following three properties:





**Consistency**

 A guarantee that **every node in a distributed cluster returns the same, most recent, successful write. Consistency refers to every client having the same view of the data.** There are various types of consistency models. Consistency in CAP \(used to prove the theorem\) refers to linearizability or sequential consistency, a very strong form of consistency.

**Availability**

**Every non-failing node returns a response for all read and write requests in a reasonable amount of time. The key word here is every.** To be available, every node on \(either side of a network partition\) must be able to respond in a reasonable amount of time.

**Partition Tolerant**

**The system continues to function and upholds its consistency guarantees in spite of network partitions**. Network partitions are a fact of life. Distributed systems guaranteeing partition tolerance can gracefully recover from partitions once the partition heals.



