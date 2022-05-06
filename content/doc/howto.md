---
title: "NeoDB使用指南"
date: 2022-04-27T20:38:59+08:00
draft: false
---

_本指南由[@chestnut@m.cmx.im](https://m.cmx.im/@chestnut)撰写，会不断完善，也欢迎您在[GitHub](https://github.com/neodb-social/about.neodb.social)使用pull request提交修改建议，或者向[NeoDB官方Fediverse帐号](https://mastodon.social/@neodb)提出意见和建议。_

# NeoDB是什么

[neodb.social](https://neodb.social/) - 致力于为联邦宇宙居民提供一个自由开放互联的书籍、电影、音乐和游戏收藏评论空间。NeoDB的源代码来自NiceDB，NiceDB由里瓣社区赞助开发。

# NeoDB使用指南

本文以Mastodon宇宙为例进行解释说明。

## 1. 如何注册NeoDB？

NeoDB目前不支持注册账号，能通过Mastodon（或Pleroma/Friendica/PixelFed）实例的账号登录。NeoDB也兼容Twitter登录，但无法享受到联邦网络互通的便利。已经有账号的网友们可以直接看第二步。

### 什么是Mastodon？

请点击以下文章了解Mastodon并根据教程选择实例注册账号，在此不再赘述。

- [《Mastodon（长毛象）使用讲解》](https://home.bangdream.space/mastodon-use/)by 炸邦裂梦乐团信息站
- [《长毛象 Mastodon 食用指南》](https://jings.blog/misc/how-to-use-mastodon.html) by Jing's Blog
- [《更加开放的社交网络，「长毛象」让你自由地分享想法》](https://sspai.com/post/46868) by i9NGbgNq@少数派
- [《去中心化开源社区Mastodon（长毛象）的使用详解 + 搭建安装教程》](https://blog.ysoup.org/tech/Mastodon.html) by YSOUP blog
- [Mastodon 中文官方文档](https://docs.joinmastodon.org/zh-cn/)

### 其他联邦宇宙？

Pleroma/Friendica/PixelFed实例同样运行在联邦网络上，与Mastodon相比用户数量略少，但各有独特有趣的功能， 这些实例之间是互联互通的，用户甚至可以在彼此间迁移。

在仔细阅读上面的文章之后，相信您已经拥有联邦宇宙实例的账号了！恭喜您来到联邦宇宙！

## 2. 如何登录NeoDB？

1. 打开[NeoDB](https://neodb.social/)，在页面正中央输入您所在实例的域名。（什么是实例域名？请查看常见问题1）
    
    ![Screenshot 2022-03-23 at 22.33.13.png](Screenshot_2022-03-23_at_22.33.13.png)

2. 点击授权登录，页面将跳转至Mastodon授权页面。
    
    ![Screenshot 2022-03-23 at 23.07.48.png](Screenshot_2022-03-23_at_23.07.48.png)
    
3. 若想使用NeoDB，请点击同意授权，页面将跳转至说明页。权限用于：
    1. 查看账号信息：用于在NeoDB上显示你的账号信息。
    2. 查看你的关注：用于在NeoDB上显示你的关注信息。
    3. 以你的身份搜索：用于NeoDB确认你的被关注信息。
    4. 查看你的屏蔽列表：不在NeoDB上展示你的屏蔽列表中的用户发布的信息。
    5. 查看你的隐藏列表：不在NeoDB上展示你的隐藏列表中的用户发布的信息。
    6. 发表嘟文：在NeoDB记录信息时，可以选择同时发表嘟文到Mastodon等联邦宇宙。
    7. 上传媒体文件：发表嘟文时，将选择的媒体文件上传到嘟文中。
4. 请在仔细阅读说明页信息后，点击下方的“CUT THE SH\*T AND GET ME IN!” 按钮进入NeoDB首页。
5. NeoDB还在不断开发中，为了您最好的体验，第一次登录NeoDB时，请仔细阅读公告页的信息（如下图）。如不慎关闭公告窗口，可在页面尾部点击最右侧的“公告栏“进行查看。
    
    ![Screenshot 2022-03-23 at 23.18.40.png](Screenshot_2022-03-23_at_23.18.40.png)
    

## 3. 如何使用NeoDB？

### 3.1 查询

在NeoDB页面上方输入想要查找的条目，敲击“回车”进行搜索。在搜索结果中点击条目，查看条目详情。在条目详情页面支持：标记、评论、添加到收藏单。

### 3.2 添加

如您想查找的条目不存在，欢迎您帮助补充NeoDB数据库！可以通过搜索结果页右侧的按钮，选择您想要添加的方式和条目类型。如果您有条目在豆瓣/ Goodreads/ Steam/ Spotify/ IMDB/ TMDB/ Bandcamp/ Bangumi等网站的链接，可以直接在页面上方的搜索栏里输入链接网址，回车即可自动导入。

![Screenshot 2022-03-23 at 23.55.48.png](Screenshot_2022-03-23_at_23.55.48.png)

## 4. 如何将标记或评论同时发表到联邦网络？

以标记想读为例，在条目页面详情页面点击“想读”按钮，跳出标记弹窗。在弹窗中（下图）选择“分享到联邦网络”，即会在“提交”后，同时在联邦网络发布嘟文。

![Screenshot 2022-04-27 at 22.46.04.png](Screenshot_2022-04-27_at_22.46.04.png)

**标签**：为嘟文添加标签，不需要使用“#”，回车后才算添加成功。默认添加标签可通过NeoDB的设置页（见下图）进行修改。

**可见性**：与联邦网络意义一致。如需设置公开选项是否发布到公共时间轴，请通过NeoDB的设置页进行修改。

![Screenshot 2022-04-27 at 22.49.39.png](Screenshot_2022-04-27_at_22.49.39.png)

## 5. 如何导入豆伴数据？

0. 首先准备好从[豆伴导出](../doufen/)的后缀名为.xlsx的豆伴备份文件。

1. 点击页面右上角的“数据”选项，进入数据导入/导出页面。
    
    ![Screenshot 2022-03-28 at 16.47.56.png](Screenshot_2022-03-28_at_16.47.56.png)
    
2. 在导入豆瓣标记数据部分，进行自定义设置后，点击导入。
    1. 自定义设置说明：
    - “导入”：选择您的豆伴数据中包含的类别。（注：上传导入由[豆伴](https://github.com/doufen-org/tofu)（豆坟）导出的Excel文件，**请勿手动修改该文件**。部分条目由于需要登陆无法自动同步。）
    - “覆盖”：选择，如果某条目在NeoDB和豆伴文件中都存在时，您期望保留哪方的数据。在如果导入数据前，已经在NeoDB对条目进行过标记，选择“覆盖原有标记”会以豆伴文件的数据对条目重新进行标记，不选择则维持原有的标记。
    - 可见性：选择所同步的标记可见性是否为公开；对于已有的标记即便覆盖也不会改变可见性。
        
        ![Screenshot 2022-03-28 at 16.53.26.png](Screenshot_2022-03-28_at_16.53.26.png)
        
    
    b. 举例说明：
    
    - 导入前
        
        ![Screenshot 2022-03-28 at 17.12.53.png](Screenshot_2022-03-28_at_17.12.53.png)
        
    - 导入中
        
        ![Screenshot 2022-03-28 at 17.15.12.png](Screenshot_2022-03-28_at_17.15.12.png)
        
    - 导入后
        
        ![Screenshot 2022-03-28 at 17.16.51.png](Screenshot_2022-03-28_at_17.16.51.png)
        
3. 点击右上角的“主页”，即可查看自己的标记数据。

## 6. 如何导入Goodreads数据？

可通过NeoDB页面右上角的“数据”选项中的“导入Goodreads账号或书单进行操作”进行操作。

![Screenshot 2022-04-27 at 23.12.57.png](Screenshot_2022-04-27_at_23.12.57.png)

## 7. 如何导出NeoDB上的个人数据？

可通过NeoDB页面右上角的“数据”选项中的“导出个人数据”进行操作。

![Screenshot 2022-04-27 at 23.04.26.png](Screenshot_2022-04-27_at_23.04.26.png)

## 8. 如何删除NeoDB上的个人数据？

可通过NeoDB页面右上角的“数据”选项最下方的“删除数据和账号信息”进行操作。

在输入框中，输入您的用户名@实例名，如user@mostodon.social，点击“永久删除”即可。删除操作无法撤销，请按需在删除前对NeoDB信息进行导出备份。

![Screenshot 2022-04-27 at 23.00.27.png](Screenshot_2022-04-27_at_23.00.27.png)

# 常见问题

## 1. 获取实例域名

### 什么是实例域名？

每个Mastodon实例都拥有自己的域名，也就是能访问到该实例的网站。以mastodon.social为例，用户可以通过 [https://mastodon.social/](https://mastodon.social/) 地址进入到这个实例的首页。

推特用户输入 twitter.com 即可。

### 如何获取所在实例域名？

每个账户的后缀即是实例域名，可以通过以下方式进行查看：

1. 点击自己的头像，进入账号主页；
2. 在自己的名字下面的以“@”开头的一串字母即是自己的账号；
3. 实例域名是第二个“@”后面的一串字母，以下图为例，实例域名为“mastodon.social"。
    
    ![Screenshot 2022-03-23 at 22.37.04.png](Screenshot_2022-03-23_at_22.37.04.png)

少数实例提供多个辅助网址方便翻墙用户使用，取决于站长的设置，部分翻墙用的域名部分也能用于登录NeoDB，但如果您在用这些辅助域名登录时遇到困难，请使用主域名登录。
