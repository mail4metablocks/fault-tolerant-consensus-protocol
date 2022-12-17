# fault-tolerant-consensus-protocol


Practical Byzantine Fault Tolerance (PBFT) and Raft are both fault-tolerant consensus protocols that are designed to ensure that a distributed system can continue to function even when some of its components fail or behave incorrectly.

PBFT is a protocol that allows a group of servers, or "replicas," to come to a consensus on the value of a distributed data store, even in the presence of faulty replicas that may behave arbitrarily. It works by having each replica send messages to all the other replicas in the system, and using these messages to agree on the current state of the data store. PBFT is designed to be efficient and scale well to large numbers of replicas, and it is often used in distributed systems that require strong consistency, such as distributed databases.

Raft is another consensus protocol that is designed to be easy to understand and implement. It works by electing a leader among the replicas in the system, and having the leader coordinate updates to the data store. If the leader fails or becomes unavailable, the other replicas can hold an election to choose a new leader. Raft is often used in distributed systems that require high availability, such as distributed databases or distributed file systems.

Both PBFT and Raft are commonly used in distributed systems to ensure that the system can continue to function even when some of its components fail. They are both widely used and well-respected protocols in the field of distributed systems.
