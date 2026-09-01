# Awesome Erlang资源大全中文版 with stars

***

### 目录

* [Erlang资源大全中文版](#awesome-erlang-cn)
  * [包管理](#包管理)
  * [发布管理](#发布管理)
  * [web框架](#web框架)
  * [HTTP](#http)
  * [测试](#测试)
  * [日志](#日志)
  * [监控](#监控)
  * [构建工具](#构建工具)
  * [网络](#网络)
  * [数据库客户端](#数据库客户端)
  * [JSON](#json)
  * [协议](#协议)
  * [消息队列](#消息队列)
  * [开发工具](#开发工具)
  * [调试](#调试)
  * [杂项](#杂项)
  * [在线教程](#在线教程)

### 包管理

*包和依赖库的管理工具*

* [hex.pm](https://hex.pm/) - 一个Erlang生态的管理工具.

### 发布管理

*发布软件的管理工具*

* [relx](https://github.com/erlware/relx) ⭐ 693 | 🐛 83 | 🌐 Erlang | 📅 2026-03-24 - 一个release发布工具.

### web框架

*web开发框架*

* [cowboy](https://github.com/ninenines/cowboy) ⭐ 7,525 | 🐛 65 | 🌐 Erlang | 📅 2026-08-25 - 一个小巧，高效的HTTP服务器.
* [MochiWeb](https://github.com/mochi/mochiweb) ⭐ 1,890 | 🐛 11 | 🌐 Erlang | 📅 2026-08-16 - 一个用来构建Web应用的轻便,高效的HTTP应用框架的Erlang库.
* [ChicagoBoss](https://github.com/ChicagoBoss/ChicagoBoss) ⭐ 1,849 | 🐛 81 | 🌐 Erlang | 📅 2022-01-10 - 一个从Rails获取灵感，而写的框架.
* [N2O](https://github.com/synrc/n2o) ⭐ 1,341 | 🐛 1 | 🌐 Erlang | 📅 2026-06-04 - WebSocket 应用服务器.
* [yaws](https://github.com/klacke/yaws) ⭐ 1,312 | 🐛 37 | 🌐 Erlang | 📅 2026-05-29 - 一个高效处理动态页面的web服务器.
* [Nitrogen](https://github.com/nitrogen/nitrogen) ⭐ 983 | 🐛 16 | 🌐 Erlang | 📅 2026-07-26 - 一个完全用Elang编写的web应用框架(包括前端，后端).
* [Zotonic](https://github.com/zotonic/zotonic) ⭐ 846 | 🐛 195 | 🌐 Erlang | 📅 2026-08-31 - 高效,实时的web框架并且包括内容管理系统.

### HTTP

*HTTP相关的库*

* [hackney](https://github.com/benoitc/hackney) ⭐ 1,417 | 🐛 16 | 🌐 Erlang | 📅 2026-08-31 - 一个小巧的Erlang HTTP客户端.
* [gun](https://github.com/ninenines/gun) ⭐ 949 | 🐛 24 | 🌐 Erlang | 📅 2026-07-28 - 支持 HTTP/1.1, SPDY 和Websocket的HTTP客户端.
* [ibrowse](https://github.com/cmullaparthi/ibrowse) ⭐ 518 | 🐛 19 | 🌐 Erlang | 📅 2026-05-01 - Erlang HTTP 客户端.
* [bullet](https://github.com/ninenines/bullet) ⚠️ Archived - 一个cowboy用到的小巧，高效，稳定的类似WebSockets的协议库.
* [lhttpc](https://github.com/esl/lhttpc) ⭐ 128 | 🐛 20 | 🌐 Erlang | 📅 2022-03-29 - 一个支持 lightweight HTTP/1.1 的客户端.

## 测试

*测试相关的库.*

* [PropEr](https://github.com/manopapad/proper) ⭐ 918 | 🐛 50 | 🌐 Erlang | 📅 2026-06-24 - 基于Property based testing的Erlang测试工具.
* [typhoon](https://github.com/zalando/typhoon) - 分布式系统的压力测试可视化工具

## 日志

*日志相关的库.*

* [logplex](https://github.com/heroku/logplex) ⚠️ Archived - Heroku log router.
* [lager](https://github.com/basho/lager) ⚠️ Archived - 一个Erlang/OTP日志框架.

## 监控

*性能监控*

* [folsom](https://github.com/boundary/folsom) ⭐ 583 | 🐛 14 | 🌐 Erlang | 📅 2018-11-07 - 一个性能度量系统.
* [Exometer](https://github.com/Feuerlabs/exometer) ⭐ 528 | 🐛 16 | 🌐 Erlang | 📅 2019-06-14 -一款监控指标的度量库，整合了folsom.
* [eper](https://github.com/massemanet/eper) ⭐ 440 | 🐛 5 | 🌐 Erlang | 📅 2018-07-06 - 一个性能相关的工具集.
* [entop](https://github.com/mazenharake/entop) ⭐ 267 | 🐛 3 | 🌐 Erlang | 📅 2019-05-29 - 一个像top命令一样的Erlang节点监控工具.

## 构建工具

*项目构建工具.*

* [rebar3](https://github.com/rebar/rebar3) ⭐ 1,818 | 🐛 227 | 🌐 Erlang | 📅 2026-08-31 - 可以管理来自[Hex.pm](https://hex.pm/)的包. 更多查看 [rebar3.org](https://www.rebar3.org/)
* [rebar](https://github.com/rebar/rebar) ⚠️ Archived - Erlang的构建工具,使用它可以方便的编译、测试erlang程序、内联驱动和打包Erlang发行版本.
* [erlang.mk](https://github.com/ninenines/erlang.mk) ⭐ 588 | 🐛 42 | 🌐 Makefile | 📅 2026-06-25 - erlang的makefile.

## 网络

*网络相关的库和工具*

* [ranch](https://github.com/ninenines/ranch) ⭐ 1,244 | 🐛 5 | 🌐 Erlang | 📅 2026-07-28 - cowboy用到的TCP网络库.
* [gen\_rpc](https://github.com/priestjim/gen_rpc) ⭐ 227 | 🐛 9 | 🌐 Erlang | 📅 2025-11-05 - 一个Erlang-VM的RPC扩展库.
* [barrel\_tcp](https://github.com/benoitc-attic/barrel_tcp) ⭐ 83 | 🐛 1 | 🌐 Erlang | 📅 2015-07-28 - 低延迟的TCP网络库.

## 数据库客户端

*数据库客户端*

* [epgsql](https://github.com/epgsql/epgsql) ⭐ 446 | 🐛 47 | 🌐 Erlang | 📅 2026-08-16 - PostgreSQL的Erlang驱动.
* [mysql-otp](https://github.com/mysql-otp/mysql-otp) ⭐ 375 | 🐛 9 | 🌐 Erlang | 📅 2025-06-10 - Erlang/OTP的mysql驱动.
* [boss\_db](https://github.com/ErlyORM/boss_db) ⭐ 275 | 🐛 61 | 🌐 Erlang | 📅 2024-01-05 - 一个数据库的虚拟层，支持多种数据库.

## JSON

*Json协议相关的库*

* [jiffy](https://github.com/davisp/jiffy) ⭐ 880 | 🐛 0 | 🌐 C | 📅 2026-07-01 - 利用NIFs解析JSON.
* [jsx](https://github.com/talentdeficit/jsx) ⭐ 696 | 🐛 25 | 🌐 Erlang | 📅 2024-06-26 - 完全用erlang编写的json解析库.
* [jsonx](https://github.com/iskra/jsonx) ⭐ 91 | 🐛 8 | 🌐 C | 📅 2016-03-30 - 用c语言实现解析json的erlang库.
* [erljson\_bench](https://github.com/davisp/erljson_bench) ⭐ 11 | 🐛 1 | 🌐 C | 📅 2015-07-14 - 各个json解析库的性能对比.

## 协议

*各种协议库*

* [gpb](https://github.com/tomas-abrahamsson/gpb) ⭐ 581 | 🐛 4 | 🌐 Erlang | 📅 2026-05-27 - 对rebar3支持非常好的protobuf库.
* [erlang\_protobuffs](https://github.com/basho/erlang_protobuffs) ⚠️ Archived - riak数据库在用的protobuf库,支持rebar.
* [msgpack-erlang](https://github.com/msgpack/msgpack-erlang) ⭐ 219 | 🐛 5 | 🌐 Erlang | 📅 2025-06-11 - MessagePack库.

## 消息队列

*消息队列服务器*

* [emqtt](https://github.com/emqtt/emqttd) ⭐ 16,679 | 🐛 167 | 🌐 Erlang | 📅 2026-08-31 - 百万级分布式开源物联网MQTT消息服务器
* [rabbitmq](https://github.com/rabbitmq/rabbitmq-server) ⭐ 13,830 | 🐛 260 | 🌐 JavaScript | 📅 2026-09-01 - 支持多种协议AMQP, STOMP, MQTT, AMQP的消息代理服务器
* [ejabberd](https://github.com/processone/ejabberd) ⭐ 6,720 | 🐛 223 | 🌐 Erlang | 📅 2026-08-27 - 著名的XMPP服务器
* [vernemq](https://github.com/erlio/vernemq) ⭐ 3,625 | 🐛 165 | 🌐 Erlang | 📅 2026-08-28 - 基于Erlang/OTP的分布式MQTT消息服务器
* [MongooseIM](https://github.com/esl/MongooseIM) ⭐ 1,751 | 🐛 32 | 🌐 Erlang | 📅 2026-08-31 - 高效的分布式XMPP服务器,ejabberd的优化版本

## 开发工具

*开发工具*

* [intellij-erlang](https://github.com/ignatov/intellij-erlang) ⭐ 752 | 🐛 273 | 🌐 Java | 📅 2026-08-17 - intellij插件.
* [distel](https://github.com/massemanet/distel) ⭐ 324 | 🐛 19 | 🌐 Emacs Lisp | 📅 2022-11-11 - emacs,erlang IDE.
* [vimerl](https://github.com/jimenezrick/vimerl) ⭐ 302 | 🐛 7 | 🌐 Erlang | 📅 2015-09-08 - 编写erlang的vim插件.

## 调试

*调试工具*

* [recon](https://github.com/ferd/recon) ⭐ 1,427 | 🐛 11 | 🌐 Erlang | 📅 2026-04-23 - 可用于生产环境的调试工具集.

## 杂项

*杂项*

* [theBeamBook](https://github.com/happi/theBeamBook) ⭐ 4,051 | 🐛 1 | 🌐 Erlang | 📅 2026-04-26 - A description of the Erlang Runtime System ERTS and the virtual Machine BEAM.
* [tsung](https://github.com/processone/tsung) ⭐ 2,629 | 🐛 130 | 🌐 Erlang | 📅 2026-03-02 - 支持HTTP, XMPP, LDAP,等多种协议的压力测试工具.
* [kerl](https://github.com/kerl/kerl) ⭐ 1,666 | 🐛 18 | 🌐 Shell | 📅 2025-06-19 - Erlang安装工具，能够轻松切换多个版本.
* [sync](https://github.com/rustyio/sync) ⭐ 761 | 🐛 17 | 🌐 Erlang | 📅 2025-06-30 - 一个开发时自动重编译的工具.
* [erlang-history](https://github.com/ferd/erlang-history) ⚠️ Archived - 在Erlang的shell中加入历史记录.

## 在线教程

*一些免费的在线资源*

* [erlang.org/docs](http://www.erlang.org/docs) - 官方文档！
* [learnyousomeerlang](http://learnyousomeerlang.com/) - 非常著名的erlang在线书籍,内容非常新.
* [tutorialspoint](https://www.tutorialspoint.com/erlang/index.htm) - [tutorialspint.com](https://www.tutorialspoint.com/)网站上的erlang入门教程.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-01._
