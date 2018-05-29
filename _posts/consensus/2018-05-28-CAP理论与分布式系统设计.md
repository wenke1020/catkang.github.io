
---                                                                                                                                      
layout: post
title: CAP理论与分布式系统设计
category: Consensus
tags: [Paxos, Raft，一致性，共识算法]
keywords: Paxos, Raft，一致性，共识算法
---

1  引言

	在现代分布式系统中，节点数目是巨大的。在CAP理论的范围内，MichaelStoneBraker
    断言分区必然会发生，并且系统内发生节点失败的机会随着节点数的增加而呈指数增加：

    ![pic](https://github.com/wenke1020/wenke1020.github.io/blob/master/pic/%E5%85%AC%E5%BC%8F.webp)


