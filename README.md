# Survey-On-Scaling-Blockchain-Using-Sharding
A Survey on Scaling Blockchain using Sharding. It is done under the guidance of Prof. Vinay Ribeiro as a part of course CS694 (Seminar).

## What is Sharding?

Sharding is a database partitioning technique where a large dataset is divided into smaller, more manageable segments called "shards." Each shard is stored on a different server, enabling parallel processing and improved performance. Sharding distributes the data and computational workload across multiple machines, facilitating horizontal scaling and enhancing system efficiency.

## How can Sharding help in Scaling Blockchain?

Sharding can significantly enhance the scalability of blockchain networks by partitioning the blockchain state and transaction processing into smaller, independent shards. This approach allows for parallel transaction processing and reduces the computational burden on individual nodes. Here are some technical benefits:

1. **Increased Throughput**: Sharding enables multiple shards to process transactions concurrently, leading to a higher transactions per second (TPS) rate. Each shard can handle a subset of the network’s transactions, collectively boosting overall throughput.

2. **Reduced Latency**: By distributing the transaction load across multiple shards, the time required for transaction validation and block confirmation decreases, resulting in lower network latency.

3. **Horizontal Scalability**: As the demand on the network grows, additional shards can be introduced, allowing the system to scale horizontally. This scaling method is more sustainable than vertical scaling, which relies on increasing the power of individual nodes.

4. **Resource Optimization**: Nodes in a sharded blockchain are responsible for maintaining only a subset of the overall state, reducing storage and computational requirements. This optimization allows for greater participation from nodes with limited resources.

5. **Fault Isolation**: In a sharded blockchain, issues in one shard (e.g., high transaction volume or a security breach) do not necessarily impact other shards. This isolation enhances the network’s resilience and reliability.

6. **Consensus Efficiency**: Sharding can improve consensus mechanisms by reducing the number of nodes required to reach consensus for each shard. This reduction can lead to faster consensus times and lower communication overhead.

7. **Cross-Shard Communication**: Efficient cross-shard communication protocols are developed to ensure seamless transaction execution across different shards. This capability maintains the integrity and consistency of the overall blockchain.

By leveraging these technical advantages, sharding addresses the scalability limitations of traditional blockchain networks, paving the way for broader adoption and diverse application scenarios.
