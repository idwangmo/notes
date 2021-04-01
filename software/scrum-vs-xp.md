# 硝烟中的 SCRUM 和 XP

## 序言

迭代开发的基本要求：

-   迭代要有固定时长——不能超过 6 个星期
-   在没一次迭代的结尾，代码都必须经过 QA 的测试，能够正常工作

Nokia 的 Scrum 标准：

-   Scrum 团队必须要有产品负责人，而且团队都应该清楚这个人呢是谁
-   产品复测人必须要有产品的 Backlog，其中包括团队对它进行的估算
-   团队必须要有燃尽图，而且要了解他们自己的生产率
-   在一个 Sprint 中，外人不能干涉团队的工作

## 第一章

Scrum 不是方法学，它是一个框架

## 第二章

> 对于实践中我遇到的情况最好是产品能将业务描述清楚，而不是考虑到技术与业务上实现的问题，有基本上的 BDD 描述，这样开发就能够根据产品的文档进行技术设计

## 第三章

在 sprint 计划会议之前，要确保产品 backlog 尽然有序

> 不是要求有完备的文档，而是对需要进行的工作有准确的描述，对产品边界上有准确的评估，并且能对自己所设计的功能有进行解释的准备，而不是 在和技术人员交流的时候死缠栏打

产品负责人之外的人能添加新的 story，但是不能对功能的考核和工作量进行估计

## 第四章

**制定 sprint 技术是在整个 Scrum 中最重要的活动**

sprint 会议应当产生的成果：

-   sprint 目标
-   团队成员名单（应当包括每个人能投入工作的程度）
-   sprint backlog
-   确定号 sprint 演示日期
-   确定好时间地点，供举行每日的 scrum 会议

当产品负责人坚持没时间不参加 sprint 会议以尝试的策略：

-   试着让产品负责人理解，为什么他的直接参与事关项目成败
-   试着在团队中找到某个人，让他在会议中充当产品负责人的代表
-   试着说服管理团队为我们分配新的产品负责人
-   推迟 sprint 的启动时间，直到产品负责人找到时间参会为止

牺牲内部质量是一个错误的决定，一旦牺牲内部质量，在后期就要 投入更多的精力取解决这些事情

学会按照时间盒安排工作，学会制定合乎情理的时间盒，这对会议长度和 sprint 长度同样有帮助

决定 story 进入到 sprint 里的方法：

1. 本能反应
2. 生产率计算

用生产率计算来估计包括两步：

1. 得出估算生产率
2. 计算在不超过估算生产率的情况下可以加入多少 story

> 产品负责人应当对团队的生产率进行合理评估，控制好产品开发的进度（评估不是给出精确的结果，而是能对 sprint 的进度有所管控）

可以在进行项目决策的使用索引卡

不要将任务拆分出现在产品的 backlog 中，原因有：

-   任务拆分的随机性较强
-   产品负责人不需要关心这种细节程度

> 对于产品负责人说，任务的细分不是其职责，任务的划分应该下放到技术负责人中，由技术团队来对任务进行划分，在此过程中，技术负责人的目标应该是对所开发的产品和 stroy 进行解释

当 Scrum 团队中测试人员说可以，这个 story 就算是结束了

> 除此之外，其他人都无法决策这个 story 是否结束（除非这个 sprint 流产）

## 第五章

> 当 sprint 结束的时候，应该向全公司发送 sprint 的信息，应当包含这个 sprint 的目标，进度，相关文档和开发人员信息，以此让公司同事了解到团队正在做的事情

## 第六章

> 将 sprint backlog 的信息公开放置到团队人员能看到的地方，以便了解进度，可以考虑结合看板和燃尽图的模式

在使用燃尽图的时候，应当将休息时间排除在外

## 第七章

**让团队坐在一期**

> 当然产品负责人应该距离团队很近，就算不能在一起，也得尽量不合开发团队的整体分开

## 第八章

当一个个人经常不能完成 sprint 中的目标，这个时候应该进行单独的辅导，如果还是这样，在衡量他不是太重要之后，就试着将他从团队中挪走

## 第十章

在进行 sprint 回顾的时候，只要能清楚的指出问题的所在，到了下一个 sprint，问题也许就自行解决了

## 第十一章

可以在两个 sprint 之间安排实验日，用于研究新的技术，学习新的技术，或者可以进行分享活动

## 第十二章

推荐书目：敏捷估计与规划

## 第十三章

测试驱动开发意味着要先写一个自动测试，然后编写恰好嫩巩固用的代码，让它通过这个测试，接着对代码进行重构，提高代码的可读性和消除重复，整理一下然后继续

## 第十四章

在一个 sprint 中及早发现并修复 bug，要比 sprint 结束后再这样做的代价小得多

> 在没个 sprint 版本中加入一些上个 sprint 后来发现的 bug 是一个很好的解决办法

## 第十五章

将各个 sprint 团队的周期保持一致是一个很好的做法

使用跨组件的团队可以很好的对功能和任务进行分配

在一个 sprint 中的 story 中，一定得分出优先级，这样才能更好有序的开发（并且可以防止中间出现意外事件）