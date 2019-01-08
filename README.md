# 说明

随便写写，随缘维护。

## 文档检索

### [blevesearch/bleve](https://github.com/blevesearch/bleve)

一个文档检索库，支持分库。

### [go-ego/riot](https://github.com/go-ego/riot)

一个文档检索库，不能分库，但更快。

### [sahilm/fuzzy](https://github.com/sahilm/fuzzy)

一个关键字模糊匹配搜索工具。

### [sergi/go-diff](https://github.com/sergi/go-diff)

类似`git diff`能力的文本差异算法库，可用来做脚本的热更新。

### [antlinker/go-dirtyfilter](https://github.com/antlinker/go-dirtyfilter)

Golang基于DFA算法实现的敏感词过滤

## 网络

### [funny/snet](https://github.com/funny/snet)

在包体协议层实现游戏断线重连、自动加密方案。（参考）

### [afex/hystrix-go](https://github.com/afex/hystrix-go)

[参考](https://studygolang.com/articles/11875)

golang版hystrix，一个容错库，旨在隔离指向远程系统，服务和第三方库的请求，杜绝级联故障，并在复杂的分布式系统中实现弹性，毕竟在分布式系统中，故障是不可避免的。

## 链路追踪

### [jaegertracing/jaeger](https://github.com/jaegertracing/jaeger)

Uber开源的go版Zipkin。

### [mitchellh/go-server-timing](https://github.com/mitchellh/go-server-timing)

一个统计链路请求时间并返回结果给前端的中间件。

## 负载均衡/网关

### [containous/traefik](https://github.com/containous/traefik)

go语言版nginx，天然支持集成k8s。

### [youtube/doorman](https://github.com/youtube/doorman)

Doorman 是一个客户端速率限制的解决方案，客户端与共享资源进行通讯，包括数据库、gRPC 服务、RESTful API 等等可使用Doorman 来限制对资源的调用。

### [GoKu](https://github.com/eolinker/GoKu-API-Gateway)

悟空API网关（开源版），是国内首个开源go语言API网关，帮助企业进行API服务治理与API性能安全维护，为企业数字化赋能。

## 消息队列

### [nsq](https://github.com/nsqio/nsq)

[文档](https://doc.yonyoucloud.com/doc/wiki/project/nsq-guide/index.html)

golang实现的消息队列。

## 任务队列

### [RichardKnop/machinery](https://github.com/RichardKnop/machinery)

一个基于消息发布的异步的任务队列。

## 数据库

### [pingcap/TiDB](https://github.com/pingcap/tidb)

[文档](https://pingcap.com/docs-cn/)

自带分布式的关系数据库，基本兼容MySql。

### [influxdata/influxdb](https://github.com/influxdata/influxdb)

时序数据库。

## Docker

### [CWSpear/local-persist](https://github.com/CWSpear/local-persist)

本地化的volume驱动。

### [portainer/portainer](https://github.com/portainer/portainer)

目前遇到最好用的DockerUI。

## 数据结构

### [jolestar/go-commons-pool](https://github.com/jolestar/go-commons-pool)

模拟`Apache Commons Pool`实现的对象池。

## 机器学习

### [esimov/pigo](https://github.com/esimov/pigo)

一个[Pico](https://github.com/nenadmarkus/pico)的golang版Face识别库。

## 并发

### [panjf2000/ants](https://github.com/panjf2000/ants)

一个协程池，带中文说明ε=(´ο｀*)))

## JSON

### [json-iterator/go](https://github.com/json-iterator/go)

目前找到的最高性能反射型JSON库。

### [bcicen/jstream](https://github.com/bcicen/jstream)

流式JSON解析库，适用于处理一些动态性更强的JSON。

### [tidwall/sjson](https://github.com/tidwall/sjson)

一个可以快速写json的库（但由于是基于字符串 tokenizer定位的，对于某些特殊字符可能坑）

## 控制台

### [AlecAivazis/survey](https://github.com/AlecAivazis/survey)

快速实现交互型控制台应用（根据N个问题，接受控制台输入），提供更友好的表现。

## UI

### [andlabs/ui](https://github.com/andlabs/ui)

一个跨平台的UI库，如果在mac下运行，需要使用open命令才能顺利打开。
