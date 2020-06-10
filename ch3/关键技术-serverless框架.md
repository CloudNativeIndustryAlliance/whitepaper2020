---
authors: [""]
company: ["华为"]
reviewers: [""]
---

Serverless的概念最早于2012年由云基础设施服务提供商 Iron.io的副总裁 Ken Fromm提出。2014年亚马逊发布Lambda开启Serverless商业化时代。2017年各大云服务提供商陆续推出Serverless服务框架，Serverless内涵得到不断丰富，从应用开发者的角度来看，使用 Serverless 框架之后，应用开发者只需要编写代码（或者函数），以及配置文件（如何 build、运行以及访问等声明式信息），然后运行 build 和 deploy 就能把应用自动部署到集群，其他事情均由 Serverless框架完成。Knative就是为解决基于容器的Serverless应用的构建、部署和运行问题的Serverless开源框架。Knative 已经被大量的厂商或平台支持，包括：Google 的 CloudRun，IBM 公有云，Pivotal 的 Riff（建立在 Knative 之上的 FaaS 系统），Openshift，Rancher RIO等。