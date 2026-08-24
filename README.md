# Awesome MySQL 资源大全中文版 with stars

我想很多程序员应该记得 GitHub 上有一个 Awesome - XXX 系列的资源整理。[awesome-mysql](http://shlomi-noach.github.io/awesome-mysql/) 就是 shlomi-noach 发起维护的 MySQL 资源列表，内容包括：分析工具、备份、性能测试、配置、部署、GUI 等。

Awesome 系列虽然挺全，但基本只对收录的资源做了极为简要的介绍，如果有更详细的中文介绍，对相应开发者的帮助会更大。这也是我们发起这个开源项目的初衷。

***

### 我们要做什么？

* 基于 awesome-sysadmin 资源列表，我们将对各个资源项进行编译整理。
* 整理后的内容，将收录在[伯乐在线资源频道](http://hao.importnew.com/)。可参考已整理的内容：
  * 《[Logstash：日志文件管理工具](http://hao.importnew.com/logstash/)》
  * 《[MyCli：支持自动补全和语法高亮的 MySQL 客户端](http://hao.importnew.com/mycli-mysql/)》

***

### 如何参与本项目？

<!-- 从下面的目录来看，本项目的工作量小不了，所以非常期待能有更多程序员一起来参与。

不过加入前，有几个小要求：

* 英文还不错，能读懂英文并用自己的话复述；
* 有 MySQL 相关实践经验；

如有兴趣，请加 QQ：50872495。加 Q 时请注明「MySQL大全」 -->

***

### 本项目的参与者

* 维护者：[tangyouhua](https://github.com/tangyouhua)

* 贡献者：[夏了夏天](http://www.importnew.com/members/wx2793649263/)、[lovecn](https://github.com/lovecn)、You

注：名单不分排名，不定期补充更新

***

<!-- ### 奖励计划

虽然奖励可能并不是你加入的主要原因，但还是有必要提一下：

* 整理超过 20 个资源后，可在伯乐在线上开通打赏；
* 每整理 20 个资源，有机会获得技术书籍或各种有意思的创意、极客产品；
* [奖励详情](http://hao.importnew.com/rewards/)

* * * -->

### 目录

* 分析工具
* 备份
* 性能测试
* 聊天应用
* 配置
* 连接器
* 部署
* 开发
* GUI
* HA
* 代理
* 复制
* 模式
* 服务器
* 分片
* 工具包

资源

* 文档
* 电子书
* 媒体
* 简讯

## 分析工具

性能，结构和数据分析工具

* [innodb-ruby](https://github.com/jeremycole/innodb_ruby) ⭐ 1,801 | 🐛 21 | 🌐 Ruby | 📅 2026-04-28 - 一个对 InooDB 格式文件的解析器，用于 Ruby 语言。
* [Anemometer](https://github.com/box/Anemometer) ⭐ 1,391 | 🐛 60 | 🌐 JavaScript | 📅 2021-12-08 - 一个 SQL 慢查询监控器。
* [innotop](https://github.com/innotop/innotop) ⭐ 803 | 🐛 27 | 🌐 Perl | 📅 2026-05-22 - 一个具备多种特性和可扩展性的 MySQL 版 'top' 工具。
* [pstop](https://github.com/sjmudd/ps-top) ⭐ 211 | 🐛 3 | 🌐 Go | 📅 2026-07-10 - 一个针对 MySQL 的类 top 程序，用于收集，汇总以及展示来自 performance\_schema 的信息。
* [mysql-statsd](https://github.com/db-art/mysql-statsd) ⭐ 101 | 🐛 6 | 🌐 Python | 📅 2021-04-20 - 一个收集 MySQL 信息的 Python 守护进程，并通过 StatsD 发送到 Graphite。

## 备份

备份/存储/恢复 工具

* [MyDumper](https://launchpad.net/mydumper) - 逻辑的，并行的 MySQL 备份/转储工具。
* [MySQLDumper](http://www.mysqldumper.net/) - 基于 web 的开源备份工具-对于共享虚拟主机非常有用。
* [mysqldump-secure](https://github.com/cytopia/mysqldump-secure) ⭐ 148 | 🐛 11 | 🌐 Shell | 📅 2022-12-15 - 将加密，压缩，日志，黑名单和 Nagios 监控一体化的 mysqldump 安全脚本。
* [Percona Xtrabackup](https://www.percona.com/doc/percona-xtrabackup) - 针对 MySQL 的一个开源热备份实用程序——在服务器的备份期间不会锁定你的数据库。

## 性能测试

*给你的服务器进行压测的工具*

* [Sysbench](https://github.com/akopytov/sysbench) ⭐ 6,780 | 🐛 217 | 🌐 C | 📅 2025-03-09 - 一个模块化，跨平台以及多线程的性能测试工具。
* [iibench-mysql](https://github.com/tmcallaghan/iibench-mysql) ⭐ 47 | 🐛 3 | 🌐 Java | 📅 2017-12-04 -基于 Java 的 MySQL/Percona/MariaDB 索引进行插入性能测试工具。

## 聊天应用

*集成进聊天室的脚本*

* [Hubot MySQL ChatOps](https://github.com/samlambert/hubot-mysql-chatops) ⭐ 89 | 🐛 0 | 🌐 CoffeeScript | 📅 2014-03-09

## 配置

*MySQL 配置实例及指导*

* [mysql-compatibility-config](https://github.com/morgo/mysql-compatibility-config) ⭐ 94 | 🐛 1 | 🌐 Shell | 📅 2017-03-02 - 使 MySQL 配置起来更像新的（或先前）的 MySQL 版本。

## 连接器

*多种编程语言的 MySQL 连接器*

* [Connector/Python](https://dev.mysql.com/downloads/connector/python/) - 一个对于 Python 平台和开发的标准化数据库驱动程序。
* [go-sql-driver](https://github.com/go-sql-driver/mysql) ⭐ 15,272 | 🐛 72 | 🌐 Go | 📅 2026-08-20 - 一个 Go 语言的轻量级、极速的 MySQL 驱动程序。
* [libAttachSQL](http://libattachsql.org/) - libAttachSQL 是 MySQL 服务器的一个轻量级，非阻塞的 C 语言 API。
* [MariaDB Java Client](https://mariadb.com/kb/en/mariadb/mariadb-connector-j/) - 针对 Java 应用且经过 LGPL 许可的 MariaDB 客户端库。
* [MySQL-Python](https://sourceforge.net/projects/mysql-python/) - 一个 Python 语言的 MySQL 数据库连接器。
* [PHP mysqlnd](https://dev.mysql.com/downloads/connector/php-mysqlnd/) - 针对 MySQL 的 MySQL 本地驱动，弃用过时的 libmysql 基础驱动。

## 开发

*支持 MySQL 相关开发的工具*

* [Flywaydb](https://flywaydb.org/getstarted/) - 数据库迁移;任意情况下轻松可靠地演变你的数据库版本。
* [Liquibase](http://www.liquibase.org/) - 对你的数据库进行源代码控制。
* [Propagator](https://github.com/outbrain/propagator) ⭐ 82 | 🐛 12 | 🌐 PHP | 📅 2014-10-26 - 集中模式和数据部署在一个多维拓扑上。

## GUI

*前端和应用的 GUI*

* [Adminer](https://www.adminer.org/) - 一个 PHP 编写的数据库管理工具。
* [HeidiSQL](http://www.heidisql.com/) - Windows 下的 MySQL 图形化管理工具。
* [MySQL Workbench](http://dev.mysql.com/downloads/workbench/) - 提供给数据库管理员和开发人员进行数据库设计和建模的集成工具环境;SQL 开发;数据库管理。
* [phpMyAdmin](https://www.phpmyadmin.net/) - 一个 PHP 写成的开源软件，意图对 web 上的 MySQL 进行管理。
* [SequelPro](https://github.com/sequelpro/sequelpro) ⭐ 9,195 | 🐛 530 | 🌐 Objective-C | 📅 2023-02-25 - 一个 mac 下运行 MySQL 的数据库管理应用程序。
* [mycli](http://hao.importnew.com/mycli-mysql/) - 一个带自动补全和语法高亮的终端版 MySQL 客户端

## HA

*高可用解决方案*

* [Galera Cluster](http://galeracluster.com/products/) - 一个基于同步复制的多主机集群方案。
* [MHA](http://code.google.com/p/mysql-master-ha/) - 针对 MySQL 的优秀高可用管理器及工具
* [MySQL Fabric](https://www.mysql.com/products/enterprise/fabric.html) - 一个用于管理 MySQL 服务器场（Server Farms）的可扩展框架。
* [Percona Replication Manager](https://github.com/percona/percona-pacemaker-agents/) ⭐ 79 | 🐛 15 | 🌐 Shell | 📅 2018-11-28 - 针对 MySQL 的异步复制管理代理。支持以文件和 GTID 为基础的复制，使用 booth 实现的地理分布式集群。

## 代理

*MySQL 代理*

* [MaxScale](https://github.com/mariadb-corporation/MaxScale) ⭐ 1,496 | 🐛 19 | 🌐 C++ | 📅 2026-01-08 - 开源，以数据库为中心的代理。
* [Mixer](https://github.com/siddontang/mixer) ⭐ 768 | 🐛 12 | 🌐 Go | 📅 2019-01-21 - Go 实现的一个 MySQL 代理，目的为 MySQL 分片提供一个简单的解决方案。
* [ProxySQL](https://github.com/renecannao/proxysql) ⭐ 26 | 🐛 0 | 🌐 C++ | 📅 2025-11-23 - 高性能的 MySQL 代理。
* [MySQL Proxy](https://launchpad.net/mysql-proxy) - 一个处于你的客户端和 MySQL 服务端之间的简单程序，它可以检测、分析或者改变它们的通信。

## 复制

*复制相关的软件*

* [orchestrator](https://github.com/outbrain/orchestrator) - 对 MySQL 复制拓扑管理并可视化的工具。
* [Tungsten Replicator](https://code.google.com/archive/p/tungsten-replicator) - MySQL 的一个高性能、开源、数据复制引擎。

## 模式

*附加模式*

* [common\_schema](https://code.google.com/archive/p/common-schema) - MySQL DBA 的框架， 提供一个具有函数库、视图库和查询脚本的解释器。
* [sys](https://github.com/mysql/mysql-sys) ⚠️ Archived - 一个视图、函数和过程的集合，以帮助 MySQL 管理人员更加深入理解 MySQL 数据库的使用。

## 服务器

*MySQL server flavors*

* [MySQL Server & MySQL Cluster](https://github.com/mysql/mysql-server) ⭐ 12,397 | 🐛 38 | 🌐 C++ | 📅 2026-08-22 - Oracle 官方的 MySQL server 和 MySQL 集群分布。
* [MariaDB](https://github.com/MariaDB/server) ⭐ 8,130 | 🐛 463 | 🌐 C++ | 📅 2026-08-24 - MySQL server 的一个由社区开发的分支。
* [WebScaleSQL](https://github.com/webscalesql/webscalesql-5.6) ⚠️ Archived - WebScaleSQL，5.6 版本，基于 MySQL 5.6 社区版本。
* [Percona Server](https://launchpad.net/percona-server) - 一个加强版的 MySQL 替代品

## 分片

*分片解决方案/框架*

* [vitess](https://github.com/youtube/vitess) ⭐ 21,242 | 🐛 1,088 | 🌐 Go | 📅 2026-08-24 - 对于大规模的 web 服务，vitess 提供服务和工具以便于 MySQL 数据库的缩放。
* [jetpants](https://github.com/tumblr/jetpants) ⭐ 1,125 | 🐛 3 | 🌐 Ruby | 📅 2017-06-15 - 一个自动化套件，用于管理大规模分片集群，由 Tumblr 开发。

## 工具包

*工具包，通用脚本*

* [go-mysql](https://github.com/siddontang/go-mysql) ⭐ 4,962 | 🐛 157 | 🌐 Go | 📅 2026-08-23 - 一个纯 go 的库，用于处理 MySQL 的网络协议和复制。
* [MySQL Utilities](https://dev.mysql.com/downloads/utilities/) - 一个命令行实用程序的集合，Python 语言编写，用于维护和管理单一或多层的 MySQL。
* [Percona Toolkit](https://www.percona.com/software/percona-toolkit) - 一个先进的命令行工具集，用于执行对于 MySQL 服务器和系统过于困难或复杂的任务。
* [openark kit](http://code.openark.org/forge/openark-kit) - 一组实用的工具，解决日常的维护工作，包括一些复杂的或需徒手操作的，用 Python 语言编写。
* [UnDROP](https://twindb.com/undrop-tool-for-innodb/) - 一个用来恢复删除或损坏的 InnoDB 表中数据的工具。

# 资源

*在这个阶段，“资源”不包括网站，博客，幻灯片，演示视频等。这些资源列表的大小令人恐惧。*

## 会议

*围绕 MySQL 进行公开，经常性的大会。*

* [FOSDEM](https://fosdem.org/) - 一个软件开发人员见面、交流思想与协作的活动。每年在 Brussels 举行。提供 “MySQL & friends” 开发工作室。
* [MySQL Central](https://www.oracle.com/openworld/mysql/index.html) - Oracle 年度 MySQL 大会，是 Oracle Open World 的一部分。
* [Percona Live](https://www.percona.com/live/conferences) - MySQL 和 OpenStack 的重要会议。
* [SCALE](https://www.socallinuxexpo.org/) - 一个每年在南加州举办，由社区组织的 Linux 和 开源软件大会。由当地 MySQL社区组织并以MySQL社区日的名义举办。

## 电子书

*MySQL 电子书以及相关材料。*

* [SQL-exercise](https://github.com/XD-DENG/SQL-exercise) ⭐ 1,531 | 🐛 8 | 📅 2023-11-11 - 包含几个 SQL 练习，包括模式描述，用 SQL 语句去建立模式，SQL 的问题及解决方案。以 wikibook SQL 练习为基础。
* [sqlfiddle](http://sqlfiddle.com/) - 在线执行 sql 测试。

## 媒体

*公开，持续的视频和音频转播。这不包括会议演讲那令人恐惧的资源列表大小。*

* [DBHangOps](http://dbhangops.github.io/) - 两周一次由各种各样的 MySQL 社区人员参加的 google 聚集大会，大会的日常就是谈论一切关于 MySQL 的东西。
* [OurSQL Podcast](http://www.oursql.com/) - MySQL 数据库社区播客。

## 新闻周刊

*顾名思义，新闻周刊\_需要一个 email 地址。下面列出周刊只需要一个 email 地址。*

* [Weekly MySQL News](http://mysqlnewsletter.com/) - 非官方的 MySQL新闻摘要，包含关于MySQL的各类信息。

<h3 id="weibo-weixin">微信公众号</h3>

* 数据分析与开发：专注分享数据库相关内容，包括：各种主流 DB 的最佳实践、数据库基础知识、性能优化、数据安全等。 <br><img src="http://ww4.sinaimg.cn/small/63918611gw1epb2c5mk0jj2046046my6.jpg" width=150 height=150>

* Linux爱好者：专注分享 Linux/Unix 相关内容，包括：工具资源、使用技巧、课程、书籍等。 <br><img src="http://ww4.sinaimg.cn/small/63918611gw1epb2ca88pfj20460463ym.jpg" width=150 height=150>

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-24._
