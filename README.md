# kafka-summary
kafka学习总结，源码剖析
目录
一、	基础篇	1
1.	开篇说明	1
2.	概念说明	1
3.	配置说明	3
4.	znode分类	17
5.	kafka协议分类	24
6.	Kafka线程	29
7.	日志存储格式	30
8.	kakfa架构设计	35
二、	流程篇	36
1、	kafka启动过程	36
2、	日志初始化和清理过程	38
3、	选举controller过程	39
4、	controller处理broker startup过程	39
5、	controller处理broker failure过程	40
6、	broker成leader、follower过程	41
7、	produce过程	43
8、	新建topic-partition过程	44
9、	consume过程	46
10、	controlled shutdown过程	47
11、	preferred election过程	47
12、	reassignment过程	47
13、	topic config change过程	48
三、	工具篇	48
四、	FAQ	52
五、	监控篇	53


