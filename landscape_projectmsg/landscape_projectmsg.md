# CNIA中国云原生技术生态图景项目信息

## 云应用定于与开发流程

### 数据库

| 项目名称 | 项目LOGO | 项目概述 | 是否开源 | 主导公司 | Github地址 |
| :-: | :-: | :-: | :-: | :-: | :-: |
| doris | ![](http://doris.apache.org/master/images/doris-logo.png) | 基于 MPP 技术的分布式、面向交互式查询的 SQL 数据仓库，主要用于解决报表和多维分析，能够在大规模数据导入尤其是密集导入数据时大幅提升SQL的性能。由百度大数据部研发，之前叫做Palo，用于解决百度凤巢报表的专用系统，2018年贡献到Apache社区中，更名为Doris。Doris在国内被众多互联网企业使用，包括新浪微博、小米、美团等。 | 是 | 百度 | https://github.com/apache/incubator-doris |
| OceanBase |   |OceanBase是由阿里巴巴、蚂蚁金服完全自主研发的金融级分布式关系数据库，始创于2010年。OceanBase具有数据强一致、高可用、高性能、在线扩展、高度兼容SQL标准和主流关系数据库、低成本等特点。OceanBase在金融行业首创“三地五中心”城市级故障自动无损容灾新标准，同时具备在线水平扩展能力，创造了6100万次/秒处理峰值的纪录。OceanBase至今已成功应用于支付宝全部核心业务。从2017年开始，OceanBase开始服务外部客户，包括建设银行、南京银行、中国人保健康、西安银行等。| 否  | |   |

### 消息和流式处理

| 项目名称 | 项目LOGO | 项目概述 | 是否开源 | 主导公司 | Github地址 |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Brpc | ![](media/15928026104680/brpc-logo.png)|  brpc又称为baidu-rpc，是百度开发一款“远程过程调用”网络框架。目前该项目已在github上开源，并且进入Apache基金孵化器。brpc的优势在于性能优异、稳定性强且对用户更易用。Brpc是百度内部C++应用中的主流远程通信框架，在开源社区中也获得了较为广泛的应用。 | 是| 百度 | https://github.com/apache/incubator-brpc |

### 应用定义与镜像制作

| 项目名称 | 项目LOGO | 项目概述 | 是否开源 | 主导公司 | Github地址|
| :-: | :-: | :-: | :-: | :-: | :-: |
| Captain |   | Captain 是一个标准的 kubernetes controller, 以 helm v3 library 为基础，参考 helm v3 design proposal 而实现。用户可以通过 HelmRequest CRD 来描述对 helm charts 的部署需求，captain 负责同步 HelmRequest 的状态并部署 helm charts。 | 是 | 灵雀云 | https://github.com/alauda/captain |

### CI/CD

| 项目名称 | 项目LOGO | 项目概述 | 是否开源 | 主导公司 | Github地址|
| :-: | :-: | :-: | :-: | :-: | :-: |

### 云原生AI应用

| 项目名称 | 项目LOGO | 项目概述 | 是否开源 | 主导公司 | Github地址|
| :-: | :-: | :-: | :-: | :-: | :-: |
| SQLFlow |  | SQLFlow是连接数据库系统和AI引擎，并使用SQL语言构建端到端人工智能任务的系统。SQLFlow支持MySQL, Hive和MaxCompute作为数据库引擎，同时支持Tensorflow, Keras和XGBoost作为机器学习引擎。SQLFlow扩展了SQL语法，支持数据预处理，自定义特征工程，模型训练，预测，评估，解释，以及求解运筹规划问题。 | 是 | 蚂蚁金服 | https://github.com/sql-machine-learning/sqlflow |
| ElasticDL |  | ElasticDL是一个Kubernetes-native弹性分布式深度学习框架，通过弹性调度提升计算集群的总体利用率和团队开发效率。ElasticDL采用Kubernetes API和动态数据分片实现了容错和弹性调度，根据优先级动态调节训练作业的资源。 使用ElasticDL也极其方便，用户只需要定义一个Keras模型，就能进行弹性分布式训练。ElasticDL实现了基于parameter server和allreduce的2种分布式训练，在包括阿里ASI和Google Cloud的Kubernetes集群上都能运行。ElasticDL框架具有很强的扩展性，还将支持PyTorch等模型训练。 | 是 | 蚂蚁金服 | https://github.com/sql-machine-learning/elasticdl |

## 云应用编排与管理

### 应用编排与调度

| 项目名称 | 项目LOGO | 项目概述 | 是否开源 | 主导公司 | Github地址|
| :-: | :-: | :-: | :-: | :-: | :-: |
| TKEStack |  | TKEStack是腾讯开源的一款集强壮性和易用性于一身的企业级容器编排引擎，基于Kubernetes，以极简的向导式界面提供了容器应用的全生命周期管理能力，帮助用户在私有云环境中敏捷、高效地构建和发布应用程序。 | 是 | 腾讯云 | https://github.com/tkestack/tke |


### 远程调度

| 项目名称 | 项目LOGO | 项目概述 | 是否开源 | 主导公司 | Github地址|
| :-: | :-: | :-: | :-: | :-: | :-: |
| SOFARPC |  | SOFARPC 是蚂蚁金服开源的一款基于 Java 实现的 RPC 服务框架，为应用之间提供远程服务调用能力，具有高可伸缩性，高容错性，目前蚂蚁金服所有的业务的相互间的 RPC 调用都是采用 SOFARPC。SOFARPC 为用户提供了负载均衡，流量转发，链路追踪，链路数据透传，故障剔除等功能。 | 是 | 蚂蚁金服 | https://github.com/sofastack/sofa-rpc |

### 网络代理

| 项目名称 | 项目LOGO | 项目概述 | 是否开源 | 主导公司 | Github地址|
| :-: | :-: | :-: | :-: | :-: | :-: |
| MOSN | :-: | MOSN 是一款使用 Go 语言开发的网络代理软件，由蚂蚁金服开源并经过几十万容器的生产级验证。 MOSN 作为云原生的网络数据平面，旨在为服务提供多协议、模块化、智能化、安全的代理能力。 MOSN 是 Modular Open Smart Network 的简称。 MOSN 可以与任何支持 xDS API 的 Service Mesh 集成，亦可以作为独立的四、七层负载均衡，API Gateway、云原生 Ingress 等使用。 | 是 | 蚂蚁金服 | https://github.com/mosn/mosn |

### API网关

| 项目名称 | 项目LOGO | 项目概述 | 是否开源 | 主导公司 | Github地址|
| :-: | :-: | :-: | :-: | :-: | :-: |
| BFE | ![](https://landscape.cncf.io/logos/bfe.svg) | BFE（Baidu Front End，百度统一前端）是百度的统一七层流量转发平台。BFE平台目前已接入百度大部分流量，每日转发请求接近1万亿，峰值QPS超过1000万。在2019年百度春晚红包活动中，BFE平台在超大用户压力、数次流量波峰下平稳运行，保证了春晚红包活动的顺利进行。BFE在2019年正式开源，目前已经进入到CNCF landscape当中。 | 是 | 百度 | https://github.com/lcnetdev/bfe |

### 云原生中间件

| 项目名称 | 项目LOGO | 项目概述 | 是否开源 | 主导公司 | Github地址|
| :-: | :-: | :-: | :-: | :-: | :-: |
| SOFAStack | :-: | SOFAStack™（Scalable Open Financial Architecture Stack）是一套用于快速构建金融级云原生架构的中间件，也是在金融场景里锤炼出来的最佳实践。 | 是 | 蚂蚁金服 | https://github.com/sofastack |
### 服务网格

| 项目名称 | 项目LOGO | 项目概述 | 是否开源 | 主导公司 | Github地址|
| :-: | :-: | :-: | :-: | :-: | :-: |

## 云原生工具集

| 项目名称 | 项目LOGO | 项目概述 | 是否开源 | 主导公司 | Github地址|
| :-: | :-: | :-: | :-: | :-: | :-: |

### 流程自动化与配置管理

| 项目名称 | 项目LOGO | 项目概述 | 是否开源 | 主导公司 | Github地址|
| :-: | :-: | :-: | :-: | :-: | :-: |

### 容器镜像仓库

| 项目名称 | 项目LOGO | 项目概述 | 是否开源 | 主导公司 | Github地址|
| :-: | :-: | :-: | :-: | :-: | :-: |

### 云原生安全技术

| 项目名称 | 项目LOGO | 项目概述 | 是否开源 | 主导公司 | Github地址|
| :-: | :-: | :-: | :-: | :-: | :-: |
| Occlum |  | Occlum 是一个面向机密计算的 TEE OS，使得应用程序不需修改，即可运行在 TEE 环境下（比如 Intel SGX）。| 是 | 蚂蚁金服 | https://github.com/occlum/occlum |

### 云端密码管理

| 项目名称 | 项目LOGO | 项目概述 | 是否开源 | 主导公司 | Github地址|
| :-: | :-: | :-: | :-: | :-: | :-: |

## 云原生底层技术
### 容器技术

| 项目名称 | 项目LOGO | 项目概述                                                     | 是否开源 | 主导公司 | Github地址 |
| -------- | -------- | ------------------------------------------------------------ | -------- | -------- | ---------- |
| BeyondVm |          | BeyondVM 胖容器是以 Docker 容器技术为基础，提供类虚拟机体验的增强的容器技术。帮助客户在不改变已有代码、体验和分工的前提下快速容器化存量应用，快速、渐进式的拥抱云原生技术。 | 否       | 博云     |            |



### 存储技术

| 项目名称 | 项目LOGO | 项目概述 | 是否开源 | 主导公司 | Github地址|
| :-: | :-: | :-: | :-: | :-: | :-: |

### 网络技术

| 项目名称     | 项目LOGO | 项目概述                                                     | 是否开源 | 主导公司 | Github地址 |
| ------------ | -------- | ------------------------------------------------------------ | -------- | -------- | ---------- |
| BeyondFabric | :-:      | BeyondFabric是一个二层网络解决方案，是基于OVS的增强版2层网络模型。具备以下功能，支持集群内外网络打通、支持容器双向限速，避免吵闹邻居、支持容器重启IP地址不变、支持指定IP地址发布服务、支持控制平面数据平面分离、支持网络隔离、支持适配传统组网模型、支持集群分区 | 否       | 博云     |            |



