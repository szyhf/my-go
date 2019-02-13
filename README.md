# 说明

随便写写，随缘维护。

## 文档字符串

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

### [gobwas/glob](https://github.com/gobwas/glob)

一个高性能的字符串（通配符？）匹配库，适用特定场景的字符串匹配，性能高于regexp。

## 网络

### [funny/snet](https://github.com/funny/snet)

在包体协议层实现游戏断线重连、自动加密方案。（参考）

### [afex/hystrix-go](https://github.com/afex/hystrix-go)

[参考](https://studygolang.com/articles/11875)

golang版hystrix，一个容错库，旨在隔离指向远程系统，服务和第三方库的请求，杜绝级联故障，并在复杂的分布式系统中实现弹性，毕竟在分布式系统中，故障是不可避免的。

### [gorilla/websocket](https://github.com/gorilla/websocket)

官方对ws的支持有点忧桑吖，还好有……

### [gobwas/ws](https://github.com/gobwas/ws)

一个更高性能(。)的ws库。

### [tidwall/evio](https://github.com/tidwall/evio)

基于事件回调实现的网络库，可以用于优化一个conn一个goroutine的问题。

### [skywind3000/kcp](https://github.com/skywind3000/kcp)

面向移动端游戏的TCP替代品，能以比TCP浪费10%-20%的带宽的代价，换取平均延迟降低 30%-40%，且最大延迟降低三倍的传输效果。纯算法实现，并不负责底层协议（如UDP）的收发，需要使用者自己定义下层数据包的发送方式，以 callback的方式提供给 KCP。 连时钟都需要外部传递进来，内部不会有任何一次系统调用。

## 链路追踪

### [jaegertracing/jaeger](https://github.com/jaegertracing/jaeger)

Uber开源的go版Zipkin。

### [mitchellh/go-server-timing](https://github.com/mitchellh/go-server-timing)

一个统计链路请求时间并返回结果给前端的中间件。

## 负载均衡/网关

### [containous/traefik](https://github.com/containous/traefik)

go语言版nginx，天然支持集成k8s，自带容器发现能力。

### [youtube/doorman](https://github.com/youtube/doorman)

Doorman 是一个客户端速率限制的解决方案，客户端与共享资源进行通讯，包括数据库、gRPC 服务、RESTful API 等等可使用Doorman 来限制对资源的调用。

### [GoKu](https://github.com/eolinker/GoKu-API-Gateway)

悟空API网关（开源版），是国内首个开源go语言API网关，帮助企业进行API服务治理与API性能安全维护，为企业数字化赋能。

## 分布式

### [etcd-io/etcd](https://github.com/etcd-io/etcd)

感觉不用多解释了，只是为了找网址记的。

### [lni/dragonboat](https://github.com/lni/dragonboat)

一个完整的Raft算法库，自带很多工具的样子，据说有足够完整的测试集合以及实际应用，而且有中文文档😶

### [chrislusf/gleam](https://github.com/chrislusf/gleam)

纯go实现的MapReduce库。

## 消息队列

### [nsq](https://github.com/nsqio/nsq)

[文档](https://doc.yonyoucloud.com/doc/wiki/project/nsq-guide/index.html)

golang实现的消息队列。

## 任务队列

### [RichardKnop/machinery](https://github.com/RichardKnop/machinery)

一个基于消息发布的异步的任务队列。

## 数据库（关系型）

### [pingcap/TiDB](https://github.com/pingcap/tidb)

[文档](https://pingcap.com/docs-cn/)

自带分布式的关系数据库，基本兼容MySql。

### [flike/kingshard](https://github.com/flike/kingshard)

Golang的MySql代理，致力于简化MySQL分库分表操作；能够让DBA通过kingshard轻松平滑地实现MySQL数据库扩容。

### [flike/kingbus](https://github.com/flike/kingbus)

基于raft强一致协议实现的分布式MySQL binlog 存储系统。它能够充当一个MySQL Slave从真正的Master上同步binglog，并存储在分布式集群中；同时又充当一个MySQL Master将集群中的binlog 同步给其他Slave。

## 数据库（时序型）

### [influxdata/influxdb](https://github.com/influxdata/influxdb)

嗯很出名不解释。

### [prometheus/prometheus](https://github.com/prometheus/prometheus)

嗯很出名不解释。

## 数据库（键值对型）

### [boltdb/bolt](https://github.com/boltdb/bolt)

嗯……

## 缓存

### [golang/groupcache](https://github.com/golang/groupcache)

带filter能力的Cache。

## Docker

### [CWSpear/local-persist](https://github.com/CWSpear/local-persist)

本地化的volume驱动。

### [portainer/portainer](https://github.com/portainer/portainer)

目前遇到最好用的DockerUI。

### [bcicen/ctop](https://github.com/bcicen/ctop)

控制台工具，可以比较好的展示当前运行的容器情况。

### [goharbor/harbor](https://github.com/goharbor/harbor)

一个相对重量级的镜像管理系统，用于自建镜像，相应的能力也更强。

## 数据结构

### [jolestar/go-commons-pool](https://github.com/jolestar/go-commons-pool)

模拟`Apache Commons Pool`实现的对象池。

### [ahmetb/go-linq](https://github.com/ahmetb/go-linq)

省事神器吖不解释，懂得自然懂。

### [PuerkitoBio/goquery](https://github.com/PuerkitoBio/goquery)

以类似jQuery的表达处理解析html的工具（可用于爬虫）。

### [gocolly/colly](https://github.com/gocolly/colly)

爬虫工具，直接结合[PuerkitoBio/goquery](https://github.com/szyhf/my-go#puerkitobiogoquery)服用效果更佳。

### [antonmedv/expr](https://github.com/antonmedv/expr)

可以按照一般的数学逻辑解析表达式并执行，支持嵌套、参数和函数等，而且接收了我的PR😜

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

## 命令行

### [spf13/cobra](https://github.com/spf13/cobra)

制造具备现代气息的控制台交互库，可以提供命令解析和组织。

## 代码管理与持续集成

### [go-gitea/gitea](https://github.com/go-gitea/gitea)

老朋友不解释。

### [drone/drone](https://github.com/drone/drone)

很出名纯备忘。

### [dominikh/go-tools](https://github.com/dominikh/go-tools)

一组golang代码质量管理工具链。

## 微服务

### [go-kit/kit](https://github.com/go-kit/kit)

一套完整的微服务框架，很有学习价值。

## 前端

### [gopherjs/gopherjs](https://github.com/gopherjs/gopherjs)

把go编译成js，感觉我跟java系八字不合，也许能解决部分问题。

### [andlabs/ui](https://github.com/andlabs/ui)

一个跨平台的UI库，如果在mac下运行，需要使用open并把可执行文件改成`*.app`才能顺利打开。

> 囧：`/usr/bin/open you_bin.app`

### [lxn/walk](https://github.com/lxn/walk)

一个Windows的GUI工具库。

### [murlokswarm/app](https://github.com/murlokswarm/app)

一个用`go`做`Web App`的框架，感觉类似`Electron`。

### [AlecAivazis/survey](https://github.com/AlecAivazis/survey)

快速实现交互型控制台应用（根据N个问题，接受控制台输入），提供更友好的表现。

## 游戏

### [hajimehoshi/ebiten](https://github.com/hajimehoshi/ebiten)

一个已经商业化的引擎，做了多款的手游开发。支持的平台非常广，用这个游戏引擎做出的游戏能够支持 PC 操作系统如 Windows、Mac、Linux、FreeBSD，也支持手机操作系统 Android、iOS，还支持 Web 开发如 GopherJS、WebAssembly。它是一个生产级的引擎。

### [davyxu/tabtoy](https://github.com/davyxu/tabtoy)

一个面向游戏开发的Excel导表工具，功能完备，设计思路让我学到了很多。

## 程序设计

### [tmrts/go-patterns](https://github.com/tmrts/go-patterns)

各种设计模式在golang的实现模板，仅供参考。

## 无所不能的其他

### [influxdata/influxql](https://github.com/influxdata/influxql)

influxql的语法解析器，用来学怎么实现自己的语言……

### [eranyanay/1m-go-websockets](https://github.com/eranyanay/1m-go-websockets)

高性能网络层参考……