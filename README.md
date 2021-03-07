# FocusBigData

![](./images/head.png)



## :elephant:Hadoop分布存储框架

+ ### Hadoop篇
  
  + [Hadoop本地模式环境搭建](pdf/hadoop)
  + [Hadoop完全分布式环境搭建](pdf/hadoop)
  + [Hadoop配置历史服务](pdf/hadoop)
  + [Hadoop配置日志聚集](pdf/hadoop)
  + [Hadoop配置集群时间同步](pdf/hadoop)
  + [Hadoop源码编译](pdf/hadoop)
  + [Hadoop集群脚本编写](pdf/hadoop)
  + [Hadoop数据压缩](pdf/hadoop)
  + [Hadoop序列化](pdf/hadoop)
  
+ ### HDFS篇
  
  + [HDFS入门概述](pdf/hadoop)
  + [HDFS命令行操作](pdf/hadoop)
  + [HDFS客户端操作 --- 开发环境准备](pdf/hadoop)
  + [HDFS客户端操作 --- 文件操作](pdf/hadoop)
  + [HDFS客户端操作 --- IO流操作](pdf/hadoop)
  + [HDFS数据读写流程](pdf/hadoop)
  + [NameNode和SecondearyNameNode](pdf/hadoop)
  + [NameNode故障处理](pdf/hadoop)
  + [集群安全模式](pdf/hadoop)
  + [DataNode相关概念](pdf/hadoop)
  + [HA高可用](pdf/hadoop)
  + [HA高可用 --- HDFS-HA集群配置](pdf/hadoop)
  + [HA高可用 --- YARN-HA集群配置](pdf/hadoop)
  + [HA高可用 --- Federation架构设](pdf/hadoop)
  
+ ### MapReduce篇

  + [MapReduce之入门概述](pdf/hadoop)
  + [MapReduce之工作流程](pdf/hadoop)
  + [MapReduce之InputFormat数据输入](pdf/hadoop)
  + [MapReduce之OutputFormat数据输出](pdf/hadoop)
  + [MapReduce之Shuffle机制](pdf/hadoop)
  + [MapReduce之MapJoin和ReduceJoin](pdf/hadoop)
  + [MapReduce之数据清洗ETL](pdf/hadoop)
  + [MapReduce优化](pdf/hadoop)

+ ### Yarn篇

  + [Yarn工作机制和作业提交流程](pdf/hadoop)
  + [Yarn任务推测执行](pdf/hadoop)

+ ### 源码篇

  + Job提交流程
  + MapTask运行
  + ReduceTask运行
  + 切片流程
  + Shuffle流程

【源码是做成思维导图的方式，放在[公众号](#微信公众号)里面，恢复`hadoop思维导图 `即可获得，思维导图部分展示如下】

![](./images/hadoop源码图.png)



## :dolphin:Spark分布式计算框架

+ ### SparkCore篇

  + [Spark基础入门和环境安装](pdf/spark)
  + [RDD编程入门](pdf/spark)
  + [RDD转换算子](pdf/spark)
  + [RDD行动算子](pdf/spark)
  + [RDD函数传递和依赖关系](pdf/spark)
  + [RDD缓存和checkpoint](pdf/spark)
  + [RDD数据分区](pdf/spark)
  + [RDD数据读取和保存](pdf/spark)
  + [RDD累加器和广播变量](pdf/spark)

+ ### SparkSql篇

  + [SparkSql之DataFrame和DataSet](pdf/spark)
  + [SparkSql之自定义UDF和UDAF函数](pdf/spark)
  + [SparkSql之数据加载和保存](pdf/spark)

+ ### SparkStreaming篇

  + [SparkStreaming之Dstream入门](pdf/spark)
  + [SparkStreaming之Dstream创建](pdf/spark)
  + [SparkStreaming之Dstream转换和输出](pdf/spark)

+ ### Spark内核篇

  + [Spark通信架构和集群启动流程](pdf/spark)
  + [Spark模式运行机制](pdf/spark)
  + [Spark任务调度机制](pdf/spark)
  + [SparkShuffle解析](pdf/spark)
  + [Spark内存管理](pdf/spark)

+ ### Spark调优篇

  + [Spark之常规性能调优](pdf/spark)
  + [Spark之算子调优](pdf/spark)
  + [Spark之Shuffle调优](pdf/spark)
  + [Spark之JVM调优](pdf/spark)
  + [Spark常见故障排查](pdf/spark)
  + [Spark数据倾斜解决方案](pdf/spark)



## :bird:Flink分布式流式框架

+ ### Flink篇

  + [Flink入门](pdf/flink)
  + [Flink部署](pdf/flink)
  + [FlinkAPI之Environment-Source-Transform-Sink](pdf/flink)
  + [Flink运行时架构](pdf/flink)
  + [FlinkAPI之数据类型和UDF函数](pdf/flink)
  + [Flink之Window概述](pdf/flink)
  + [Flink之时间语义和WaterMark](pdf/flink)
  + [Flink之ProcessFunctionAPI](pdf/flink)
  + [Flink之状态编程](pdf/flink)
  + [Flink之容错机制chekpoint](pdf/flink)
  + [Flink之CEP复杂时间处理](pdf/flink)

+ ### FlinkSql篇

  + [FlinkSql之入门概述](pdf/flink)
  + [FlinkSql之Table操作](pdf/flink)
  + [FlinkSql之流式持续查询](pdf/flink)
  + [FlinkSql之窗口](pdf/flink)
  + [FlinkSql之函数](pdf/flink)


> ​	最近利用工作之余给给大家先更新了Hadoop、Spark、Flink三个大数据中最主要的框架，后面还陆续给大家跟新如下内容：【公众号第一时间发布文章，后面在同步到各个平台】

- Hive数据仓库
- Zookeeper分布式协调框架
- HBase列式存储分布式数据库
- Elasticsearch开源搜索引擎
- Kafka消息队列
- Flume数据传输框架
- Sqoop数据传输框架
- Azkaban调度框架
- Kylin分析型数据仓库
- Impala实时查询分析引擎
- Hue大数据web管理器
- Kudu列式存储分布式数据库
- Kettle开源的ETL工具
- DataX阿里开源ETL工具
- ClickHouse开源列式数据库
- Ambari大数据平台搭建利器
- Ranger大数据权限管理利器
- Airflow调度和监控工作流的平台
- Griffin数据质量监控工具
- Tableau大数据分析工具
- Pulsar大数据分析工具
- Atlas元数据治理工具
- Filebeat数据采集工具
- Saiku数据分析工具
- Superset大数据可视化的利器
- Sentry大数据权限管理框架
- Zabbix集群监控工具
- Zepplin数据交互可视化工具



## 数据仓库系列

>【待更新】
>
>- 数据仓库概念
>- 数据仓库建模
>- 数仓分层
>- 数据集市和数据中台和数据仓库区别
>- 数据治理是什么
>- 项目技术选型
>- 系统数据流程设计
>- 服务器选型
>- 集群资源规划
>- 数据埋点设计
>- 数据采集设计
>- 电商业务术语和流程
>- 数据同步策略
>- 漏斗分析
>- 数据监控查询和可视化



## 关于我

> ​	说起来在工作中已经有一段时间没有使用大数据了，被我们总监拉去做人工智能【:cry:】，主要做图像识别和目标物体检测，然后装在tx2小车上跑，太多算法真的看的头都大了，而且关键之前我还没做过，只能硬着头皮学了机器学习和深度学习算法【所以大家想入门AI也可以找我，不过深入就不行了】，过程痛并快乐着，最后也能出了个模型【其实就是调参炼丹，懂的都懂】。未来我想做的技术还是大数据方向的，尤其是流式计算，后面我在星球中会有很大篇幅来讲流式计算，创作不易，希望大家支持一下，愿与诸君共勉。【可加我咨询，记得备注git】【图片加载不出来可以搜索：focusbigdata】

<img src="./images/个人微信扫码图.jpg" style="zoom:33%;" />

