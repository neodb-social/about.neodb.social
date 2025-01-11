---
title: "使用豆伴插件导出数据"
date: 2022-04-28T20:38:59+08:00
draft: false
---

[豆伴](https://doufen.org/)（又称豆坟）是一款浏览器扩展程序，可以安装在Chrome/Vivaldi/Opera/Edge/Brave等电脑浏览器中，用于备份自己的豆瓣数据到本机，然后再从本机上传到NeoDB。以下来自[豆伴官方说明](https://github.com/doufen-org/tofu):

# 豆伴：豆瓣账号备份工具
一款 Chrome 扩展程序，用于备份豆瓣账号数据。

## 安装

此工具基于 Chrome 扩展开发，所以需先安装 Chromium 内核浏览器才能使用。请先检查你的系统种是否已经安装了此类浏览器。常见的 Chromium 内核浏览器有：[Chrome](https://www.google.com/chrome/)、[Opera](https://www.opera.com/)、[Vivaldi](https://vivaldi.com/) 等。如果你所在的地区无法访问 Chrome 浏览器的官方网站，建议使用 [Vivaldi](https://vivaldi.com/) 浏览器代替。为了你的系统安全，请务必**不要**安装从其他任何**非官方渠道**（特别是国内某搜索引擎推荐的链接）下载的 Chrome 浏览器。

### 1. Chrome 网上应用商店

如果你所在的地区可以访问 [Chrome 网上应用商店](https://chrome.google.com/webstore/category/extensions)，请直接前往：
https://chrome.google.com/webstore/detail/ghppfgfeoafdcaebjoglabppkfmbcjdd
进行在线安装。

如果无法打开上面的链接，请选择其他安装方式。

### 2. 本地安装扩展

如果你系统中安装了 Chromium 内核的浏览器，可以前往 https://download.doufen.org/ 下载打包的扩展程序，进行本地安装。

安装方法：

1. 将下载的压缩包解压缩后保存到本地文件夹中；
2. 打开浏览器主菜单，选择「`更多工具`」-「`扩展程序`」，或者直接在浏览器地址栏内打开「`chrome://extensions/`」；
3. 开启页面右上角的「`开发者模式`」选项；
4. 点击「`加载已解压的扩展程序`」按钮，选择刚才保存的文件夹。

### 3. 使用「豆坟」浏览器

为了方便 Windows 用户，特地制作了**开箱即用**的「豆坟」浏览器，可以前往 https://download.doufen.org/ 下载。「豆坟」浏览器是一个修改过的 Chromium 浏览器，无需通过 Chrome 网上应用商店便可安装「豆伴」扩展程序。

「豆坟」浏览器无需安装，下载后解压缩保存到本地，双击运行「豆坟.exe」。启动浏览器窗口后，会自动下载并安装「豆伴」扩展程序。安装完毕后，会在浏览器地址栏右侧出现「豆伴」扩展程序的图标。



## 使用

成功安装后，你会在浏览器地址栏右侧看到扩展的图标。如果没有找到图标，可能需要前往「`扩展程序`」页面开启此扩展程序。

![](open.png)

### 1. 备份数据

请先在浏览器中打开豆瓣并登录你的账号。然后点击扩展程序图标，在下拉菜单中选择「`新建任务`」，在对话框中选择你要备份的项目，点击「`新建`」按钮开始备份。

![](new1.png)

![](new2.png)

### 2. 浏览备份

备份完成后，可以在刚才的下拉菜单中，选择「`浏览备份`」来查看备份的内容。你可以点击浏览视图右上角的「`导出数据`」按钮，将数据导出到 Excel 表格中。

![](export.png)

导出得到的文件可以在NeoDB的「数据」页面导入。
