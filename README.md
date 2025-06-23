# DDD
DDD领域驱动设计
#### 什么是DDD领域驱动设计
    1.以领域为中心，聚焦业务本身，而不是技术细节；
    2.隔离限界上下文；
    3.通用语言，使用相同的术语，减少沟通障碍；

#### 分析问题
    先从调用链去考虑，controller->service->dao，那我们的业务service是依赖
    dao，dao是技术细节框架，例如JPA/Mybatis

#### 实现方法
    controller->service<-dao


