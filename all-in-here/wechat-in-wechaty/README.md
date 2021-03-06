# Wechat-Go

## 功能概述

WeChat-GO 将依靠微信机器人解决群主自动邀请加群、群内签到管理、群员发广告自动被踢出、群内每周统一分享技术文章、新加入群员受到欢迎以及更多还没有想到的功能。

> 如果您有任何疑问，请到[Issues][1] 反馈。

## 快速上手

* 第一步：Fork 或直接 Clone 本仓库至本地
* 第二步：确认本地是否搭建 Node.js 环境和 Docker 环境(详见下方“参考链接”)
* 第三步-1：有两种方式启动项目：npm 或 docker，本项目暂时采用官方推荐的 docker run：

```
docker run -ti --volume="$(pwd)":/bot --rm zixia/wechaty mybot.ts
```

* 第三步-2：有两种方式启动项目：npm 或 docker，这里是使用 npm 的情况：

```
cnpm install
node mybot.js
```

> 如果您有任何疑问，请到[Issues][2] 反馈。

## TODO 计划列表

- [x] 群主自动邀请加群
- [x] 新加入群员受到欢迎
- [ ] 可识别某人表情包并自动回复此表情包
- [ ] 群内签到管理
- [ ] 群员发广告自动被踢出
- [ ] 群内每周统一分享技术文章

## 贡献指南

如果您想为 WeChat-Go 贡献代码，请采用 fork + pull request 方式，并在发起 PR 前先将 master 上超前的代码 rebase 到自己的分支上。

## 贡献者

* [韩亦乐][3]
* Waiting for U…

## 加入测试

丢丢机器人群内将及时测试最新的机器人，加我好友，注明“丢丢”或“WeChat-GO”，拉你入群。

![韩亦乐的个人微信号](public/wechat-me.png)

## 参考链接

* [wechaty][9]: 本项目依赖库
* [getting-started-wechaty][10]
* [Docker 从入门到实践][11]
* [Docker 入门实战][12]
* [Docker 入门教程][13]

## 开源许可

本项目采用 [GPL 许可证](http://www.gnu.org/licenses/gpl.html) 进行许可。

[1]:	https://github.com/hylerrix/wechat-go/issues
[2]:	https://github.com/hylerrix/wechat-go/issues
[3]:	https://github.com/hylerrix
[9]:	https://github.com/Chatie/wechaty
[10]:	https://blog.chatie.io/guide/2017/01/01/getting-started-wechaty.html
[11]:	https://www.gitbook.com/book/yeasy/docker_practice/details
[12]:	https://yuedu.baidu.com/ebook/d817967416fc700abb68fca1?fr=aladdin&key=docker&f=read###
[13]:	http://www.docker.org.cn/book/docker/what-is-docker-16.html