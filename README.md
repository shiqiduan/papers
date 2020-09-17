# papers
A repository for good papers to read. 

## Links

------

1. [Distributed Systems Engineering](https://pdos.csail.mit.edu/6.824/schedule.html)

2. [What is a Distributed Systems Engineer?](https://www.ably.io/blog/what-is-a-distributed-systems-engineer)

3. [An introduction to distributed systems](https://github.com/aphyr/distsys-class)

4. [Hidden scaling issues of distributed systems - System design in the real world](https://www.ably.io/blog/hidden-scaling-issues-of-distributed-systems-real-world/)

   1. 一些关于构建分布式系统的实践中的经验和见解，将分布式系统的关键概念和真实软件开发活动进行关联讨论。核心理念是构建满足用户需求的系统，从概念出发，选择优先级高的问题进行解决。同时认识到分布式系统开发是复杂的，如何控制复杂度和人员组织的匹配，less is more。这个经验非常重要。也是我忽视的。

      软件开发的实践经验不存在银弹，最重要的是持续有节奏的输出价值.

5. https://www.evernote.com/shard/s125/u/0/sh/7f0fa7e3-fe6b-42bc-bb94-f9d52b334c70/2ac6b5aa9ff908e381cb548a8170d555

   讨论GFS里面的数据一致性问题.

6. http://www.cs.columbia.edu/~nahum/w6998/papers/ton97-timing-wheels.pdf

   1. 时间轮，一种定时设施的实现

7. https://www.cnblogs.com/hzmark/p/ubiq.html

   1. google内部使用的，可扩展支持容错的日志处理框架
   2. 跟spark、storm、flink等的区别在于，ubiq支持跨数据中心的容错能力
   3. 支持exactly-once
   4. 在未来，我们计划为Ubiq开发面向服务的架构，以实现更有效的访问控制，隔离和资源管理。 我们还在探索使用机器学习模型进行精细级资源管理和预测控制。

8. [TODO] The Chubby lock service for loosely-coupled distributed systems -zookeeper

9. [TODO] Finding a Needle in Haystack: Facebook's Photo Storage

10. [TODO] Resilient Distributed Datasets: A Fault-Tolerant Abstraction for In-Memory Cluster Computing

    1. spark

11. [TODO] Spanner: Google's Globally-Distributed Database

12. [TODO] Dynamo: Amazon’s Highly Available Key-value Store



## 顶会

------

### OSDI

MapReduce，BigTable，Chubby，Spanner，DryadLINQ，KLEE，Ceph，TensorFlow 等等

### SOSP

包括 GFS，Dynamo，sel4，等等，都是发表在 SOSP 上的。