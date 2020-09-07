# 2020.9.6
- 每日上班流程：搜索论文，加入mendeley。查看问题时及时解决，并将本日内容与解决思想写入github
- 有效工具：mdeditor写笔记 mendeley download-chrome dblp sdu图书馆
- bounded-retrieval
- Incompressible Encodings是否能在检索效率的优化上做出成就？
- 模拟 不可区分 选择安全 自适应 规约 区分器 敌手 随机预言机 究竟是什么关系？
https://zhuanlan.zhihu.com/p/104290214 安全性刻画
- 看完 混淆电路与不可区分混淆 算是找回了之前的记忆。
- 配置sophos
# 2020.9.7
### 下午组会
配置rocksdb:https://blog.csdn.net/fanpengfei0/article/details/53385732
grpc:https://www.jianshu.com/p/d84afd56b82d wrong

简单理解两种不同的安全模型
|可证明安全/不可区分安全/基于游戏   |   基于模拟|
| ------------ | ------------ |
|  IND-CPA IND-CCA etc 挑战者 区分器 敌手|  可简单看作敌手vs系统 |
| ------------ | ------------ |
| 主要用到的思想是归约| 💡ideal vs real|

我们充当挑战者，挑战敌手。
去年jianghan老师讲的就是不可区分安全，模拟从论文中学来。
视图是静态的，模拟就是多个视图的重叠。

