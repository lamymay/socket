
客户端与zookeeper断开连接后，该节点被删除，只是Zookeeper给该节点名称进行顺序编号


订阅
长连接loop对服务端压力大

节点数据
存储数据较小，官方推荐小于1M

配置一致
存储配置文件
配置信息




负载均衡再客户端
Zookeeper与nginx负载均衡与
负载均衡器，不同负载算法

基于服务器的负载均衡，
基于客户端的负载均衡，

Zookeeper会给注册的客户端推送服务器的列表

方向不同：决定权再服务器


命名服务/服务注册发现/服务发现/


保持独占，保持时序
抢占锁：

/isLock_task_100

先创建并定义一个时间窗，然后去做业务，最后删除该节点

表示
记录会话信息，保存到
item_002
item_003
item_004
item_005

Master/Slave
主备
两个服务是同时提供服务还是只有一个

主备<-->客户端
主备节点的选择有客户端选择

两台机器都在线，数据一致性问题












springboot 动态加载配置文件


























































 






部署:单机、集群

集群中的角色
Leader
Follow
Observer

Leader
Follow
处理

Observer
不参与投票，其他与follow一样


只有一个节点写


集群最低需要几个机器
最低3个（2N+1）

ACL权限控制模式


zookeeper特性
工作原理

服务器状态


数据同步流程


最终一致性


集群中动态扩展
高版本的可以，

宕机之后如何处理？
重启，替代不行（IP），只能加入新的节点

Java客户端 Curator
创建节点，根节点可以递归来创建或者删除，简化开发
分布式的锁

chubby非开源的

2181--对client
2888--




比特币，分布式记账本
挖矿，争夺记账权



















