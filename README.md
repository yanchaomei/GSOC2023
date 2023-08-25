# GSoC 2023 Implement python client for RocketMQ 5.0: Final Report
**Mentee**: Chaomei Yan, yanchaomei@mail.ustc.edu.cn

**Mentor**: Aaron Ai, Apache RocketMQ PMC Member, yangkun.ayk@gmail.com

**Project Website**: https://rocketmq.apache.org/

**Project GitHub**: https://github.com/apache/rocketmq-clients

## About
RocketMQ 5.0 has released various language clients including Java, CPP, and Golang, to cover all major programming languages, a Python client needs to be implemented.
## Background
### Apache RocketMQ
Apache RocketMQ is a distributed messaging and streaming platform with low latency, high performance and reliability, trillion-level capacity and flexible scalability.
### Apache RocketMQ Clients
RocketMQ Clients - Collection of Client Bindings for Apache RocketMQ
Client bindings for Apache RocketMQ, as known as RocketMQ 5.x SDK. All of them follow the specification of rocketmq-apis, replacing 4.x remoting-based counterparts. Clients in this repository are built on top of Protocol Buffers and gRPC.
## Contribution
### Issue
https://github.com/apache/rocketmq-clients/issues/382 (Assigned)

### Pull Request
[Pull Request #508](https://github.com/apache/rocketmq-clients/pull/508) (Status: Merged)
[Pull Request #513](https://github.com/apache/rocketmq-clients/pull/513) (Status: Merged)
[Pull Request #528](https://github.com/apache/rocketmq-clients/pull/528) (Status: Merged)
[Pull Request #530](https://github.com/apache/rocketmq-clients/pull/530) (Status: Merged)
[Pull Request #533](https://github.com/apache/rocketmq-clients/pull/533) (Status: Merged)
[Pull Request #546](https://github.com/apache/rocketmq-clients/pull/546) (Status: Merged)
[Pull Request #559](https://github.com/apache/rocketmq-clients/pull/559) (Status: Merged)
[Pull Request #588](https://github.com/apache/rocketmq-clients/pull/588) (Status: Merged)

## Conclusion
In this project, we design and implement a Python Client for RocketMQ 5.0. In this way, developers can use python client to connect to RocketMQ.
## Future Work
In the future, we plan to add push consumer for python client
## Acknowledgement
This project is supported by the Google Summer of Code program and The Apache Software Foundation. Firstly, I want to thank my mentor, Aaron Ai, who guides me through the whole project, especially but not limited to design, implementation, code review, and community bonding. Secondly, I want to thank the Apache RocketMQ community contributors for their inspirable issue and pull request activities.
