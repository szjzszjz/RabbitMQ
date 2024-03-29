# RabbitMQ
遵循JMS的RabbitMQ消息中间件

### 主流消息中间件介绍
#### 1. ActiveMQ
activeMQ 是Apache出品，最流行，能力强劲的开源消息总线，并且它是一个完全支持JMS规范的消息中间件。  
其丰富的API，多种集群构建模式使得他成为业界老牌消息中间件，在中小型企业中应用广泛！  
MQ衡量指标：服务性能，数据存储，集群架构  
![activemq](https://github.com/szjzszjz/RabbitMQ/blob/master/src/main/resources/static/activemq.png)

#### 2. Kafka  
kafka是linkedIn开源的分布式发布-订阅消息系统，目前归属于Apache顶级项目。kafka主要特点是基于Pull的模式来处理消息消费，追求高吞吐量。一开始的目的就是用于日志收集和传输。0.8版本开始支持复制，不支持事务，对消息的重复、丢失、错误没有严格要求，适合产生大量数据的互联网服务的数据收集业务。  
![kafka](https://github.com/szjzszjz/RabbitMQ/blob/master/src/main/resources/static/kafka.png)

#### 3. RocketMQ  
rocketMQ 是阿里开源的消息中间件，目前已经孵化为Apache的顶级项目，他是纯Java开发，具有高吞吐量、高可用性，适合大规模分布式系统应用的特点。RocketMQ思路起源于kafka,他对消息的可靠传输及事务性做了优化，目前在阿里集团被广泛用于交易，充值、流计算、消息推送、日志流式处理，binglog分发等场景。  
![rocketmq](https://github.com/szjzszjz/RabbitMQ/blob/master/src/main/resources/static/rocketmq.png)

#### 4. RabbitMQ  
RabbitMQ是使用Erlang语言开发的开源消息队列系统，基于AMQP协议来实现。AMQP的主要特性是面向消息、队列、路由（包括点对点和发布-订阅）、可靠性、安全。AMQP协议更多用在企业系统内，对哦数据一致性、稳定性和可靠性要求很高的场景，对性能和吞吐量的要求还在其次。  
![rabbitmq](https://github.com/szjzszjz/RabbitMQ/blob/master/src/main/resources/static/rabbitmq.png)
