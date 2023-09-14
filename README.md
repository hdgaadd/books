# 高性能MySQL

## 第1章 MySQL架构与历史

### 1.1 MySQL逻辑架构

### 1.2 并发控制

### 1.3 事务

### 1.4 多版本并发控制

```
多版本并发控制：MVCC
```

### 1.5 MySQL的存储引擎

### 1.6 MySQL时间线(Timeline)

### 1.7 MySQL的开发模式

### 1.8 总结

## 第2章 MySQL基准测试

### 2.1 为什么需要基准测试

### 2.2 基准测试的策略

```
吞吐量指的是单位时间内的事务处理数
性能 == 响应时间
```

### 2.3 基准测试方法

```
平均值有时候是没有用的，它会掩盖掉一些真实情况
```

### 2.4 基准测试工具

### 2.5 基准测试案例

### 2.6 总结

## 第3章 服务器性能解析

### 3.1 性能优化简介

### 3.2 对应用程序进行性能剖析

### 3.3 剖析MySQL查询

### 3.4 诊断间接性问题

### 3.5 其他剖析工具

### 3.6 总结

## 第4章 Schema与数据类型优化

### 4.1 选择优化的数据类型

```
索引值尽量不要有NULL的值
```

### 4.2 MySQL schema设计中的陷阱

### 4.3 范式和反范式

```
反范式指的是不用多表关联保存数据
```

### 4.4 缓存表和汇总表

```
对表字段进行操作时，MODIFY COLUMN操作会导致表重建，而ALTER COLUMN不会
```

### 4.5 加快ALTER TABLE操作的速度

### 4.6 总结

## 第五章 创建高性能的索引

### 5.1 索引基础

### 5.2 索引的优点

### 5.3 高性能的索引策略

### 5.4 索引案例学习

### 5.5 维护索引和表

### 5.6 总结

## 第六章 查询性能优化

### 6.1 为什么查询速度会慢

### 6.2 慢查询基础：优化数据访问

### 6.3 重构查询的方式

### 6.4 查询执行的基础

# 商业的本质

## 第一章 让痛苦烟消云散

### 协同力：时刻辅佐工作的进行

### 使命与行动

### 让"结果"证明一切

### 提升领导力，从今天做起

## 第二章 越挫越强

### 力挽狂澜

## 第三章 增长是王道

### 为公司注入新鲜血液

### 要集中资源，不要分散资源

### 重新定义创新，让每个人参与其中

### 利用最优秀的人才实现增长计划

### 为员工提供合理的薪资

### 通过任何必要的手段拉拢那些抵制增长计划的人

## 第四章 错综复杂的全球化

### 问题一：你的全球化方案是互利共赢的吗？

### 问题二：你的外派人员拥有“洞察力”这个最宝贵的品质吗？

### 问题三：你认真考虑过风险吗？

### 问题四：我们充分开发了海外业务的潜力吗？

## 第五章 财务其实很简单

### 我们的生意运行到底有多健康

### 收支平衡

### 损益表

### 数据是用来比较的

### 认真审阅，努力核查

## 第六章 如何做好市场营销

### 产品：屡经考验，仍然可靠

### 渠道、渠道、还是渠道

### 价格和消费者接受度

### 宣传：亮出真功夫

### 营销团队不应对外隔绝

### B2B营销

## 第七章 大数据时代的危机管理

### 预防危机的原则

## 第八章 领导力2.0

### 探求真实，否则一无是处

### “信任”产生的好处

### 利用一切，建立互信

## 第九章 建立一个卓越的团队


# 程序员修炼之道：通向务实的最高境界

## 第1章 务实的哲学

### 1 人生是你的

### 2 我的源码被猫吃了

### 3 软件的熵

### 4 石头做的汤和煮熟的青蛙

### 5 够好即可的软件

### 6 知识组合

### 7 交流

## 第2章 务实的方法

### 8 优秀设计的精髓

### 9 DRY–邪恶的重复

### 10 正交性

### 11 可逆性

### 12 曳光弹

### 13 原型与便签

### 14 领域语言

### 15 估算

## 第3章 基础工具

### 16 纯文本的威力

### 17 Shell游戏

### 18 加强编辑能力

### 19 版本控制

### 20 调试

### 21 文本处理

### 22 工程日记

## 第4章 务实的偏执

```
务实的程序员则更进一步，他们连自己也不相信
```

### 23 契约式设计

```
契约就是确保朴实无欺的最佳方案之一
```

### 24 死掉的程序不会说谎

### 25 断言式编程

### 26 如何保存资源的平衡

### 27 不要冲出前灯范围

## 第5章 宁弯不折

```
为了跟上当今近乎疯狂的变化速度，我们需要尽一切努力编写尽可能宽松、灵活的代码
```

### 28 解耦

### 29 在现实世界中抛球杂耍

### 30 变换式编程

### 31 继承税

### 32 配置

## 第6章 并发

### 33 打破时域耦合

### 34 共享状态是不正确的状态

### 35 角色与进程

### 36 黑板

## 第7章 当你编码时

### 37 听从蜥蜴脑

### 38 巧合式编程

### 39 算法速度

### 40 重构

### 41 为编码测试

### 42 基于特性测试

### 43 出门在外注意安全

### 44 事物命名

## 第8章 项目启动之前

### 45 需求之坑

```
程序员反馈需求，帮助客户完善他们的想法
```

### 46 处理无法解决的问题

### 47 携手共建

### 48 敏捷的本质

## 第9章 务实的项目

### 49 务实的团队

```
程序员像猫
```

### 50 椰子派不上用场

### 51 务实的入门套件

### 52 取悦用户

### 53 傲慢与偏见

# 淘宝技术这十年

```
前部分讲了淘宝如何牛逼，后部分吹了淘宝的人牛逼（有许多新颖的技术可以提高眼界；感叹现在新颖的、高新的技术，在十几年前就已经出现且应用）
```

## 第1章 个人网站

### LAMP架构的网站

### 武侠和倒立文化的起源

## 第2章 个人网站的升级

### 数据库从mySQL到Oracle

### 支付手段的创新–支付宝

```
担保交易
```

### 交流方式的创新–淘宝旺旺

## 第3章 企业级Java网站

### 脱胎换骨的升级–更换开发语言

### 坚如磐石–围绕性能、容量和成本的进化

## 第4章 创造技术

### 淘宝文件系统–TFS

### 淘宝KV缓存系统–Tair

## 第5章 分别是电子商务操作系统

### 服务化

### 中间件

### Session框架

## 第6章 我在淘宝这八年

```
不会有收益的东西：很难操作的东西，用户不知道怎么玩
```

## 第7章 牛P列传

### 正明–集团核心系统高级研究员

### 正祥–淘宝高级研究员，OceanBase项目负责人

### 毕玄–集团核心系统资深技术专家

### 放翁–淘宝开放平台项目负责人

### 吴翰清–阿里云集团信息安全中心高级安全专家

### 云铮–数据平台与产品部资深技术专家

### 小马–淘宝UED前端通用平台高级技术专家

### 淘宝传奇工程师多隆的程序世界
