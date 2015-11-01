## RP 主机和 GreenShadow 现已关闭

感谢大家在三年多时间里的关注和支持，精子对 RP 主机这个项目同样有很深的感情，随着精子离开学校开始工作，精子离「每个月只有十元钱却希望建一个网站」的这群人越来越远了，精子也觉得自己没有时间和精力去处理 RP 主机的琐碎工作了，所以最后决定关闭 RP 主机。

至于 GreenShadow 的关闭，则是因为众所周知的原因。

## 时间轴

* 2012.03, 精子因为负担不起 Linode 的开销，创建了 RP 主机的前身 [神马终端](https://web.archive.org/web/20121024080726/http://what.jybox.net/)，靠邮件沟通和手工操作的方式公开出售虚拟主机。
* 2012.12, 精子用 PHP 编写了 [第一个版本的 RootPanel](https://github.com/jysperm/RootPanel2/tree/v1), 新购入了一个美国的 VPS, 并将神马终端更名为 [RP 主机](https://web.archive.org/web/20130514082953/http://rp.jybox.net/)。
* 2013.06, 精子编写了 [第二个版本的 RootPanel](https://github.com/jysperm/RootPanel2/tree/v2.0), 支持了更复杂的站点配置，和 [更完整的权限控制](https://jysperm.me/2013/05/810/)，并在 V2EX 发了一个 [广告贴](https://www.v2ex.com/t/71903)，这是 RP 主机最活跃的一段时间。
* 2013.07, 精子在香港又增加了一个节点，使用 [2.2 版本的 RootPanel](https://github.com/jysperm/RootPanel2/tree/v2.2), 但后来因为反复被 DDoS, 不得不取消了香港节点。
* 2014.05, 花了一年时间，精子用 Node.js 彻底重写了 [RootPanel](https://github.com/jysperm/RootPanel), 经过长达三个月的 [测试和迭代](https://github.com/jysperm/RootPanel/releases)，终于在 2014.8 月 [正式上线](https://web.archive.org/web/20151018231309/http://jp1.rpvhost.net/) 了。
* 2014.09, 精子为 GreenShadow 加上了 Shadowsocks 插件，上线了一个叫 [GreenShadow](https://web.archive.org/web/20150412101654/http://www.v2ex.com/t/131432) 的 ShadowSocks 服务。
* 2014.11, GreenShadow [更新了一个版本](https://github.com/jysperm/RootPanel/releases/tag/v0.8.0)，利用 Shadowsocks 的多用户特性，支持更多用户同时使用；这个版本也包含了一些本来为 RP 主机设计的功能（例如 Supervisor），但后来并没有被更新到 RP 主机。
* 2015.05, 精子不想继续维护 RP 主机了，决定关闭新用户注册、停止充值，将 RP 主机 [暂时免费](https://web.archive.org/web/20150926131234/http://blog.rpvhost.net/)。
* 2015.09, 精子发现 GreenShadow 已经在国内的部分地区无法使用了，于是精子也关闭了 GreenShadow 的注册和充值。
* 2015.10, 精子决定彻底关闭 RP 主机和 GreenShadow.

## 关闭计划

* RP 主机（两个节点）于 2016 年 3 月末关闭
* GreenShadow 于 2015 年 12 月末关闭

## 联系方式

退款、咨询请发邮件至 [jysperm@gmail.com](jysperm@gmail.com).

## 同类服务推荐

* [LeanCloud](https://leancloud.cn) 提供结构化数据存储服务来代替传统后端，亦可运行普通的 Node.js 和 Python 程序
* [Linode](https://www.linode.com/?r=a196912d910d9eefa806a2f2a00e5991811f85ef) 是传统 Linux VPS 服务商，在亚洲、欧洲、美洲有多处机房
* [DigitalOcean](https://www.digitalocean.com/?refcode=3adfb872a7c3) 是一家性价比很高的 VPS 服务商, 亦在世界各地有多个机房
* [青云](https://www.qingcloud.com) 提供服务器、储存、数据库等技术设施，支持灵活的组合和扩容，亦有香港节点
* [七牛](https://portal.qiniu.com/signup?code=3le7dofycwdw2) 提供文件和静态资源托管和加速服务
* [DaoCloud](https://account.daocloud.io/signup?invite_code=7c730iszkh25ygaknsd8) 是一个基于 Docker 的持续集成和应用发布平台
* [Heroku](http://heroku.com) 是一家老牌的 PaaS 服务商，支持众多编程语言
* [Laravel Forge](https://forge.laravel.com) 是 Laravel 官方提供的 PHP 程序的部署服务

## 资料存档

* RootPanel2 源代码（2014.8 之前）：<https://github.com/jysperm/RootPanel2>
* RootPanel3 源代码（2014.8 之后）：<https://github.com/jysperm/RootPanel>
