# Scalability
Scalability is the property of a system to handle a growing amount of work by adding resources to the system.[1]

Scalability is an ability to adjust the system to the desired capacity, which usually means handle more and more workloads cost-efficiently.[2]

When we talk about high scale products, these workloads often represent users, stored data, transactions or number of requests, all of it related to growing without affecting the user experience.[2]

# Vertical scale (scale-up)
Scaling up is relatively simple, it just about adding more resources on server's hardware, like CPU and memory, or improve disk performance changing it to a faster one.[2]

When we talk about high scale products, these workloads often represent users, stored data, transactions or number of requests, all of it related to growing without affecting the user experience.[2]

This strategy is quick and usually doesn't require any architectural change, especially in cloud computing, where it is possible to increase the capacity of a virtual machine with a few clicks.[2]
However, you can soon reach the hardware limit that can be used on the same server, you cannot increase the size of RAM or the amount of CPUs infinitely.[2]

Powerful servers are expensive, e.g. an m4.2xlarge AWS EC2 server has 8 CPUs, 32 GB of RAM and costs $302 monthly if you need to add 16 GB of RAM you will actually have to double the amount of memory since the next level of this kind of server on AWS is the m4.4xlarge with 16 CPUs, 64 GB of RAM and costs exactly double, $604 / month.[2]

Moreover, centralizing processing on a single server is not a good idea as it can be dangerous, because it's not a fault-tolerant strategy, since the whole system will be unavailable if the server crash.[2]

## Horizontal scale (scale-out)
Horizontal scaling (scaling out) means the ability to scale by adding more resources, such as new nodes , computers or containers to an overall system such as a cluster, in order to distrubute the load.[3]

It aims to make use of low-cost, off-the-shelf hardware, also called commodity hardware, instead of spending a lot of money on a single powerful machine.[3]


However, investing in software engineering usually is complex and expensive at the beginning as you have to hire a larger team and more experienced professionals to achieve the architectural design needed to scaling out. [2]

The ability to scale applications horizontally is a great achievement that can be done only software architecture techniques and technologies designed for this purpose.[2]

#Notes
Scaling bir ekonomi problemi.Çoğu zaman insanların zamanı donanım ücretlerinden daha değerli.Ölçekleme ihtiyacı doğduğunda alt yapıya kaynak eklemek problemi çözüyorsa ilk önce bunu deneyin.[4]



## References
1. ^Bondi, André B. (2000). Characteristics of scalability and their impact on performance. Proceedings of the second international workshop on Software and performance – WOSP '00. p. 195. doi:10.1145/350391.350432. ISBN 158113195X.

2. ^W.Felix(2019).https://dev.to/wfelix/scaling-up-vs-scaling-out-vertical-vs-horizontal-scalability-lc3

3.^Onur Yılmaz, Süleyman Akbaş(2019)- Introduction to DevOps with Kubernetes(Packtpub)

4.^ Ahmet Alp Balkan(2020)-https://www.youtube.com/watch?v=yw85ehdVWYg







