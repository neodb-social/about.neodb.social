---
title: "NeoDB 应用"
date: 2026-06-13T17:45:00-04:00
draft: false
weight: 20
---

NeoDB 的网页端可以在桌面和手机浏览器里使用，也是目前功能最完整的入口。刚开始使用时，建议先用网页端完成注册、绑定备用登录方式、导入旧数据、搜索条目和整理设置；之后再按自己的习惯选择手机应用或 Mastodon 兼容客户端。

![NeoDB 登录页可以选择通行密钥、电子邮件、Fediverse 或 Bluesky 登录](/doc/howto/neodb-2026-login.png)

## 网页端适合做什么

网页端覆盖 NeoDB 的完整功能集合：

- 搜索、创建和编辑书影音游播客条目。
- 标记想读、在读、已读，想看、在看、看过等状态。
- 写短评、长评、笔记、标签和收藏单。
- 导入豆瓣、Goodreads、StoryGraph、Letterboxd、RateYourMusic、Steam、播客 OPML 等旧数据。
- 管理账号、电子邮件、通行密钥、联邦宇宙身份、Bluesky 身份、同步设置和数据导出。

如果遇到第三方应用里找不到的设置或操作，优先回到网页端处理。

## NeoDB 原生应用

一些第三方开发者正在维护 NeoDB 专用应用。它们不是 NeoDB 官方应用，功能范围、发布渠道和维护状态可能会变化，安装前请查看各自说明。

iOS：

- [Piecelet](https://piecelet.app)，由 `@piecelet@mastodon.social` 开发：[App Store](https://apps.apple.com/app/piecelet-for-neodb/id6739444863) / [源代码](https://github.com/lcandy2/neodb-app)
- [Chihu](https://chihu.app)，由 `@chihu@mastodon.social` 开发：[App Store](https://apps.apple.com/app/chihu/id6737745206) / [源代码](https://github.com/nunesdennis/Chihu)
- [Fedicat](https://fedicat.com/)，由 `@fedicat@pc.cafe` 开发：[TestFlight](https://testflight.apple.com/join/b6GatWTY) / [源代码](https://codeberg.org/technicat/fedicat)

Android：

- NeoComment，由 `@mohammadrafigh@fosstodon.org` 开发：[源代码](https://github.com/mohammadrafigh/NeoComment/)
- NeoDB You，由 `@neodb_you@mastodon.social` 开发：[F-Droid](https://f-droid.org/packages/day.vitayuzu.neodb/) / [IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/day.vitayuzu.neodb) / [源代码](https://github.com/heddxh/NeoDB-You/)

## Mastodon 兼容应用

NeoDB 支持 Mastodon 的 API，所以很多 Mastodon 客户端可以登录 NeoDB 实例。它们适合处理社交时间线相关的功能：

- 发布短帖和图片。
- 查看时间线、回复、点赞、转发和书签。
- 在书签页找到正在阅读等进行中的条目，并通过回复写笔记。

但 Mastodon 兼容客户端并不是完整的 NeoDB 客户端。目录搜索、导入导出、条目元数据编辑、收藏单管理、账号安全设置等操作，仍建议使用网页端或 NeoDB 专用应用。

登录 Mastodon 兼容客户端时，服务器域名填写 `neodb.social`，然后按客户端提示授权。授权第三方应用前，确认它来自可信来源；不再使用的客户端，可以回到 NeoDB 的账号或授权管理页面撤销。

## 笔记入口

如果你主要想在手机上记录阅读笔记，可以使用 Mastodon 兼容客户端的 `书签` 页面。把书先在网页端标记为 `在读`，NeoDB 会按你的设置自动把对应动态加入书签；在客户端里回复这条书签，就会变成这本书的笔记。

具体写法见[笔记说明](/doc/notes/)。

## 登录安全

如果你最初是用 Mastodon 或 Bluesky 授权注册 NeoDB，建议尽快在 `账号` 页面绑定电子邮件，或添加通行密钥作为备用登录方式。这样即使 Mastodon 实例临时故障、上游账号丢失、应用密码失效，仍然可以回到 NeoDB。

## 参考资料

- [NeoDB 应用列表](https://neodb.net/apps/)
- [NeoDB 源代码仓库](https://github.com/neodb-social/neodb)
