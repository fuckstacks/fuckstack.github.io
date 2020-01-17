---
layout: post
title:  "小白专用の Jekyll + Github Pages 博客发布教程"
date:   2018-01-22 12:00:00 +0800
categories: Direction
---

如果你是不小心捡到一个博客的小白，那么恭喜你，这篇文章就是写给你看的。<br>
(没错，说的就是你。)

没猜错的话，小白的电脑应该是 windows 7 之类的，那这个教程就以 win7 为基础吧。

(小白：停停停！)<br>
小白的心里其实很疑惑：你不能说博客是我的，它就是我的，第一我要试一下，因为我不愿意写完之后还被别人加特技... ...(省略一万字)<br>
那你说我的博客在哪，它凭什么是我的？<br><br>

### 加载博客项目

博客现在放在一个很远的电脑上，那个电脑叫 Github，<br>
小白前几天拿到的 Github 账户密码，就是打开博客的钥匙，<br>
而且，Github 是个只认钥匙不认人的主，所以小白不能随便把钥匙借给别人。
当然，通过之前记录的邮箱，小白可以自行修改 Github 的账户密码。<br>
[修改密码传送门][github-modifyPassword]

有了钥匙，我们可以拿它跟 Github 索要博客项目了。<br>
首先，要下载一个跟 Github 沟通的对讲机。<br>
[对讲机下载传送门][github-download]

下载到哪里都可以，因为这只是一个安装包，安装完就可以删除了。
下载完成之后双击打开，<br><br>
![Untitled Image](http://p2zucbwmj.bkt.clouddn.com/5SqWX)
<br>显示这个页面，应用正在自动安装。

安装完成后，桌面会出现这个图标：<br>
![Untitled Image](http://p2zucbwmj.bkt.clouddn.com/qXrx8)
<br>记住是 “Github Desktop”，然后就可以把刚刚的安装包删除。

打开应用主界面，点击 Clone a repository 准备下载博客项目：

![Untitled Image](http://p2zucbwmj.bkt.clouddn.com/S3YIA)

下载之前需要登录，点击 Sign in 填入账户密码，继续 Sign in：

![Untitled Image](http://p2zucbwmj.bkt.clouddn.com/AzRMB)

然后设置项目要放的位置：

![Untitled Image](http://p2zucbwmj.bkt.clouddn.com/8yqyu)

点击 Clone 之后，项目开始下载。<br>
稍作等待，就可以在你刚刚选择的目录下看到这个东西：<br>
![Untitled Image](http://p2zucbwmj.bkt.clouddn.com/wSXF7)

恭喜你，博客已经下载到你的电脑中。
<br><br>

### 安装设置编辑器

编辑博客需要下载博客编辑工具：<br>
[博客编辑工具传送门][workmark-download]

这次下载下来的直接是个 zip 压缩文件，点击解压：<br>
![Untitled Image](http://p2zucbwmj.bkt.clouddn.com/GhKqk)

这个东西就是编辑器所在的文件夹，我们把它移动到放软件的地方，<br>
像小白经常使用的 C 盘，其他盘也行，防止被误删。<br>
移动完成之后，双击进入这个文件夹，找到这个文件：

![Untitled Image](http://p2zucbwmj.bkt.clouddn.com/sxr4A)

“鼠标右键 - 发送到 - 桌面快捷方式”:

![Untitled Image](http://p2zucbwmj.bkt.clouddn.com/4YNDF)

然后桌面就出现了这个图标：

![Untitled Image](http://p2zucbwmj.bkt.clouddn.com/HrQcC)
<br>双击打开。

在出现的应用界面左下角，找到 + 号，点击添加文件夹：

![Untitled Image](http://p2zucbwmj.bkt.clouddn.com/bs5rU)
<br>找到刚刚下载的 echospage.github.io 文件夹：

![Untitled Image](http://p2zucbwmj.bkt.clouddn.com/TyRQc)

双击进入，选中 _posts 点击选择文件夹：

![Untitled Image](http://p2zucbwmj.bkt.clouddn.com/df5Dn)

这时，WordMark 的左边栏出现了 _posts 目录，鼠标右键 - 新文件 就可以往里面创建新博客，点击其他文件就可以修改旧博客。

![Untitled Image](http://p2zucbwmj.bkt.clouddn.com/mj405)
<br><br>

### 开始编写博客

创建在 _posts 文件夹里面的 .md 文件会自动生成文章页面，<br>
这个文件的命名非常严格："时间-主题.md" 可以点击一下其他文件，再作修改。

![Untitled Image](http://p2zucbwmj.bkt.clouddn.com/ABXRO)

文章开头有一个文章属性的东西，到其他文章复制过来填好就行：<br>
![Untitled Image](http://p2zucbwmj.bkt.clouddn.com/9waGx)

正文的东西就可以随便你写啦~<br>
写之前学一下 MD 语法：<br>
[MD 语法传送门][markdown-learn]

编辑完成之后保存，然后打开 Github Desktop：

![Untitled Image](http://p2zucbwmj.bkt.clouddn.com/VqKw3)

提交修改之后，博客就自动更新啦~<br>
[博客传送门][eudemonia-url]

[github-modifyPassword]: https://github.com/password_reset
[github-download]: https://desktop.githubusercontent.com/releases/1.0.12-6fd0d962/GitHubDesktopSetup.exe
[workmark-download]: https://github.com/wordmark/wordmark/releases/download/v2.2.5/WordMark-win32-x64.zip
[markdown-learn]: https://www.jianshu.com/p/22ba695a7ce3
[eudemonia-url]: http://eudemonia.xyz