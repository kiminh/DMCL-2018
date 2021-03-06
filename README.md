# DMCL-2018
DMCL_2018级新生学习资料整理:smile:
文档包括基础理论知识的整理与相应的project的展示:smirk:
> ps.目前待补充的部分都是完全没有资料的部分，需要收集大家的笔记资料进行添加。对于已经有的希望大家多多上传资料，多多进行补充，尽量完善文档
## 理论
### Part1
&emsp;第一部分主要为数据结构相关，内容有：
- [BloomFilter / CuckooFilter](https://github.com/dmclNewbee302/DMCL-2018/blob/master/Theory/Part1_DataStructure/Bloom%20Filter%20%E4%B8%8E%20Cuckoo%20Filter%E6%A6%82%E5%BF%B5%E4%B8%8E%E6%AF%94%E8%BE%83.md)
- [B-Tree / B+Tree / LSM Tree](https://github.com/dmclNewbee302/DMCL-2018/blob/master/Theory/Part1_DataStructure/B%20Tree%20B%2B%20Tree%20%E4%B8%8E%20LSM%20Tree%E7%AE%80%E4%BB%8B%E4%B8%8E%E6%AF%94%E8%BE%83.md)
- [漫画介绍B-Tree](https://github.com/dmclNewbee302/DMCL-2018/blob/master/Theory/Part1_DataStructure/%E6%BC%AB%E7%94%BB%E7%AE%97%E6%B3%95%EF%BC%9A%E4%BB%80%E4%B9%88%E6%98%AF%20B%20%E6%A0%91.md)
- [SkipList](https://github.com/dmclNewbee302/DMCL-2018/blob/master/Theory/Part1_DataStructure/%E8%B7%B3%E8%A1%A8.md)

### Part2
&emsp;第二部分主要为数据库相关知识，内容有：
- [事务](https://github.com/dmclNewbee302/DMCL-2018/blob/master/Theory/Part2_DB_Transaction/%E4%BA%8B%E5%8A%A1.md)
- [并发控制](https://github.com/dmclNewbee302/DMCL-2018/blob/master/Theory/Part2_DB_Transaction/%E5%B9%B6%E5%8F%91%E6%8E%A7%E5%88%B6.md) 
- [持久化与故障恢复](https://github.com/dmclNewbee302/DMCL-2018/blob/master/Theory/Part2_DB_Transaction/%E6%8C%81%E4%B9%85%E5%8C%96%E4%B8%8E%E6%95%85%E9%9A%9C%E6%81%A2%E5%A4%8D.md)


### Part3
&emsp;第三部分主要为一致性相关，内容有：
- [一致性hash环以及chord环](https://github.com/dmclNewbee302/DMCL-2018/blob/master/Theory/Part3_Consistency/%E4%B8%80%E8%87%B4%E6%80%A7%E5%93%88%E5%B8%8C%E5%92%8Cchord%E7%8E%AF.md)
- [CAP&&BASE](https://github.com/dmclNewbee302/DMCL-2018/blob/master/Theory/Part3_Consistency/CAP%E5%AE%9A%E7%90%86.md)
- [2PC/3PC](https://github.com/dmclNewbee302/DMCL-2018/blob/master/Theory/Part3_Consistency/2PC_3PC.md)
- [拜占庭将军问题](./Theory/Part3_Consistency/拜占庭将军问题.md)

### Part4
&emsp;第四部分主要为一致性相关，内容有：
- [Paxos](https://github.com/dmclNewbee302/DMCL-2018/blob/master/Theory/Part4_DistributedConsensus/paxos%E8%BF%87%E7%A8%8B%E6%8E%A8%E5%AF%BC.md)
- [Raft](https://github.com/dmclNewbee302/DMCL-2018/blob/master/Theory/Part4_DistributedConsensus/raft-zh_cn.md) 
- [Gossip](https://github.com/dmclNewbee302/DMCL-2018/blob/master/Theory/Part4_DistributedConsensus/gossip.md)
- [BigTable](./Theory/Part4_DistributedConsensus/Bigtable.md)
- [Dynamo](./Theory/Part4_DistributedConsensus/DynamoDB.md)

## 项目
- [BloomFilter and CuckooFilter](./Project/BloomFilter_CuckooFilter)
- [ConstencyControl](./Project/ConcurrencyControl)
- [HashRing](https://github.com/Mclarenyang/ConsistentHash)
- [Raft](./Project/Raft)
