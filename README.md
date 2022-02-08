# GitHub 简易指南

## 为什么要看这篇指南

如果你是刚刚开始学习编程的学生, 想要了解和学习如何使用 GitHub, 那么, 你找对教程了!

这就是你最应该看的 GitHub 指南.

看完这篇指南, 你将会收获:

* [对 GitHub 功能的基本了解](#什么是-github)
* [对 GitHub 界面的基本了解](#github-repo-界面简易解释)
* [版本控制工具 Git 的基础使用](#git-介绍)
* [基础的 Markdown 写作](#github-文档)
* [你的第一个 Pull Request 实践!](#实战-提交你的第一个-pull-request)
* [了解如何使用 GitHub 进行团队协作](#团队协作)

[这篇文章的 GitHub 地址](https://github.com/OrangeX4/GitHub-Tutorials), 欢迎 Star!

[这篇文章的博客地址](https://orangex4.cool/post/github-tutorials-for-beginner/), 欢迎访问!

封面图:

![](https://pic4.zhimg.com/80/v2-b6c2a3ca328d995aa75ecfd6c560ccdf_720w.png)

<!-- more -->

## 什么是 GitHub

先放上这张图镇楼:

![](https://pic2.zhimg.com/80/7c9d3403bf922b1663f56975869c829b_720w.jpg?source=1940ef5c)

(图片来源 [如何使用 GitHub](https://www.zhihu.com/question/20070065/answer/79557687))

当然, 这只是开个玩笑, 虽然你在看过 [这个项目](https://github.com/komeiji-satori/Dress) 之后可能并不觉得这是一个玩笑.

咳咳, 言归正传, 按照 Wiki 的定义, **GitHub** 应该是:

> **GitHub** 是通过 **Git** 进行版本控制的软件源代码托管服务平台.

听不懂？听不懂就对了, 这篇文章就是为你而写的！

**GitHub** 其实是一个:

* **全世界最大的代码托管平台**, 你可以在上面找到绝大多数的开源代码；
* **团队协作开发平台**, GitHub 上有完善的协作功能(Fork, Issue, Pull Request 等功能)；
* **文档**, GitHub 使用 Markdown 作为文档的书写语言, GitHub 上也存在许多技术文档.
* **广告和简历**, GitHub 上聚集了世界上最多的程序员, 有许多人拿 GitHub 作为个人简历的亮点, 或者进行技术类相关的宣传；
* **免费博客**, GitHub 提供了免费的静态网站托管服务 GitHub Page；
* **自动集成**, 自动集成就是在你提交代码时或者定时进行类似的部署处理, 比如自动进行各种浪费时间的打卡任务(


## 创建账号与创建仓库

首先你要确保你能正常地访问 GitHub, 如果不能, 请自行寻找解决方法, 本指南不负责相关指导.

1. 打开 GitHub, 你能看见一个炫酷的界面, 这时候你应该点 `Sign up`, 进入账号注册的流程.

![](https://pic2.zhimg.com/80/v2-8013fffb78b29d184f480e96cd3be21d_720w.png)

2. 紧接着, 填入你的用户名, 邮箱和密码, 再点击 `Create account`.

![](https://pic1.zhimg.com/80/v2-d784b154194737aa4b9b2c909e95863c_720w.png)

3. 经过一系列选择, 验证邮箱之后, 看见这个页面, 选择 `Create a repository`, 创建你的第一个仓库.

![](https://pic3.zhimg.com/80/v2-081efaa7c1f10d6c1368e7d957860a22_720w.png)

4. 填写仓库的名称, 介绍和其他配置.

![](https://pic4.zhimg.com/80/v2-6ff1755492708b5f8bb483258f1b7f07_720w.png)

5. 当你看见这样的提示, 他是在提醒你进行后续操作, 恭喜你, 你的第一个代码仓库创建成功了!

![](https://pic4.zhimg.com/80/v2-261bfd442dddf0c645aba0a06ceb875f_720w.png)


## Git 基础使用

### Git 介绍

Q: 什么是 **Git**？

A: **Git** 是一种分布式版本控制工具, 换句话说, 是一种管理 "代码历史记录" 的工具.

Q: Git 和 GitHub 又有什么关系呢?

A: Git 先于 GitHub 出现, Git 是一种版本控制工具, 是一个在你电脑运行的工具. 而 GitHub 是依托于 Git 的代码托管平台, 是一个网站.

Q: 使用 GitHub 一定要使用 Git 吗?

A: 是的, 想要真正地使用 GitHub, 你必须得先学会 Git. 但这并不意味着你要称为 Git 专家, Git 只是一个工具, 你只需要学会基础地使用就行了.

### Git 安装

如果你是 Linux 用户, 请运行 `sudo apt-get install git` 命令安装 Git.

如果你是 Mac 用户, 请参见 [brew.sh](https://brew.sh/).

如果你是 Windows 用户, 请访问 [Git](https://pc.qq.com/detail/13/detail_22693.html) 下载与安装 Git.

安装过程中不断点 `Next` 进行默认安装就好.

![](https://pic2.zhimg.com/80/v2-1d68462aca1926f6c0e325f07c45c2d5_720w.png)

安装完成后, 请打开你的命令行终端, 输入命令 `git`, 回车.

(终端打开方式 Win 键, 输入 cmd, 或者 powershell, 回车)

![](https://pic4.zhimg.com/80/v2-75a3f608362367bcd5f56825395bd12b_720w.png)

如有如图的输出显示, 那么你就成功安装 Git 了.

### Git 使用

请参考 [廖雪峰的 Git 教程](https://www.liaoxuefeng.com/wiki/896043488029600).

你不需要非常认真地将其全部记住, 只需要简单地浏览, 知道 Git 有些什么功能, 再将其当作工具书, 需要时再翻看即可.

最基本, 你也需要掌握 Git 的这些内容:

![](https://pic2.zhimg.com/80/v2-33f6c9791ac5abd328a981d5c80a278d_720w.png)

简单来说, 你要学会:

1. 使用 `git init` 命令建立版本库;
2. 使用 `git add *` 命令将更新的文件加入版本库缓存区;
3. 使用 `git commit -m "更新内容"` 命令进行 Commit, 每一次 Commit 就相当于保存一份备份, 作为时间线的一个节点;
4. 使用 `git log` 命令查看完整时间线, 方便进行版本回退;
5. 使用 `git reset --hard <commit_id>` 进行版本回退, 即返回你保存的某个备份, `<commit_id>` 是你使用 `git log` 看见的 ID 值;
6. **如何使用 Git 将本地的版本库推送到 GitHub;**
7. 使用 `git clone <url>` 命令将 GitHub 上的代码仓库给 Clone 下来.
8. 使用 `git pull` 拉取远程分支(团队其他人可能修改了代码), 如果有冲突, 解决冲突;
9. 使用 `git push` 推送分支到远程分支, 进行团队同步;

### VSCode 与 Git

如果你用的是宇宙第一文本编辑器 VSCode 的话, 你可以很便利地进行 Git 操作.

VSCode 左端有一个版本控制面板, 如图, 你可以很简便地使用.

![](https://pic4.zhimg.com/80/v2-f0f778cfee09eb9bb0e0008f57e640af_720w.png)


## GitHub 文档

不出所料的话, 你已经在 GitHub 成功创建了自己的第一个代码仓库了.

接下来, 你要给你的仓库加一些介绍文档: `README.md`.

如图, 在 GitHub 新建 Repo 后, 照着 GitHub 的说明执行:

![](https://pic2.zhimg.com/80/v2-d4975102f1f08c67a0071511d4e40e8d_720w.png)

``` sh
echo "# first-repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/OrangeX5/first-repo.git
git push -u origin main
```

PS: 记得先按照 Git 教程里说的, 在 GitHub 加入你的 SSH key 噢.

然后你的 `README.md` 文件将会以 Markdown 形式展示在你的仓库页面.

![](https://pic2.zhimg.com/80/v2-18e9ca0fe4071670e7568d39feb154f1_720w.png)

**Markdown** 的语法非常简单, 比如:


``` markdown
# 一级标题
## 二级标题
### 三级标题

每写完一个段落要隔一行空行.

就像这样, 隔了一行空行.

---

分割线

**重点加粗**

*斜体*

~~删除线~~

---

列表:

* 并列列表项
  * 嵌套并列列表项
  * 嵌套并列列表项
* 并列列表项
* 并列列表项

1. 列表项 1
   1. 并列列表项 1
   2. 并列列表项 2
2. 列表项 2
3. 列表项 3

---

引用文本:

> 引用别人说的话
> 就这样写
> By. OrangeX4

---

这是 `行内代码` 语法.

代码块语法:

''' python
print("Hello, World!")
'''

请将 ' 替换成 `.

---

[超链接名称](链接地址)

![图片提示语](图片地址)

---

表格:

| 表头 | 表头 |
|------|------|
| 内容 | 内容 |
| 内容 | 内容 | 

---

数学公式:

行内 $x^2+y^2=1$

公式块

$$
x^2+y^2=1
$$
```

你已经掌握了 Markdown 的写作方式了!

实际上 Markdown 一般会被渲染成 HTML, 所以你也可以在里面使用 HTML 标签.


## GitHub Repo 界面简易解释

### Code 页面

![](https://pic4.zhimg.com/80/v2-b6c2a3ca328d995aa75ecfd6c560ccdf_720w.png)

### Issues 页面

![](https://pic4.zhimg.com/80/v2-904f8cd0065be0e56c90cc879b3678c7_720w.png)

### Pull requests 页面

![](https://pic4.zhimg.com/80/v2-0200a5cd2f228d92ec4c6f0333c1916b_720w.png)

一般来说, Pull Request 的流程是:
1. 先 Fork 这个 Repo, 你就有了这个 Repo 的一个专属你的复制版 Repo;
2. 用 Git Clone 克隆到本地, 进行你想进行的代码修改;
3. Git Push 到你的复制版远程仓库;
4. 提一个 Pull Request 给原来的 Repo.

整个流程会在后续详细说明, 你可以体验到你的第一个 Pull Request.


## 实战! 提交你的第一个 Pull Request

### Fork 项目

Fork 一个你要提交 Pull Request 的项目.

[First-Pull-Requests](https://github.com/OrangeX4/First-Pull-Requests) 是我创建的一个 Repo, 你可以在这里尝试提交你的第一个 Pull Request.

![](https://pic3.zhimg.com/80/v2-1ec5d4220e95acffbd4d229f6b4c1d56_720w.png)

点击右上方的 `Fork` 按钮, 你可以看见这个 Repo 已经被你 Fork 了下来, 即复制了一份.

![](https://pic4.zhimg.com/80/v2-2c2a00667d1ad67ae54622e62b5dece3_720w.png)

### 加入内容

点击这个铅笔按钮, 进入编辑模式.

![](https://pic1.zhimg.com/80/v2-0811a67202794eaf8f2cf3384273bc54_720w.png)

按照格式加入你要加入的内容, 在这里是你的名字和评论.

![](https://pic2.zhimg.com/80/v2-6e14941c1c261ce2eeade0868b844b15_720w.png)

输入 Commit 信息, 点击下面的 Commit 按钮.

![](https://pic1.zhimg.com/80/v2-32ec867a732c91c2a33948a88e675b6c_720w.png)

可以看见, 在你 Fork 出来的 Repo 中, 内容已经发生了改变.

![](https://pic3.zhimg.com/80/v2-e6eaee4be08e5f1893da6f67b3847cba_720w.png)

### 发送 Pull Request

点击你 Fork 的仓库中的 Pull request 按钮:

![](https://pic2.zhimg.com/80/v2-cdb24afc8d624a00bd301b34d0651911_720w.png)

接下来的页面会显示你修改的内容, 确实无误后点击 `Create pull request` 按钮.

![](https://pic3.zhimg.com/80/v2-9081bf3f17ebdc5193a1061e1f49fe5e_720w.png)

接下来是添加一些你的 Pull Request 的描述, 保证你的 Pull Request 能打动原 Repo, 让其同意接收.

![](https://pic3.zhimg.com/80/v2-d1734e21e22fb6a104b79e96be977872_720w.png)

然后原 Repo 就会出现你的 Pull Request, 你只需要静静等待对方回复即可!

![](https://pic4.zhimg.com/80/v2-b921e322472f46a0e44e8f09c851fa2b_720w.png)

### 同意 Pull Request

如果你收到了一个 Pull Request, 经过代码审查后, 你可以 Merge 这个 Pull Request 到你的仓库中.

![](https://pic3.zhimg.com/80/v2-e7bcaa5396fe84ee9d4a4fdcd7b9fb9e_720w.png)

最后, 可以看见, Pull Request 的内容以及被合并到原 Repo 里了!

![](https://pic1.zhimg.com/80/v2-0d72d797b38eac54daaed769c4dfd58c_720w.png)

这就是一个 Pull Request 的完整流程.

## GitHub 团队协作

如果你是**队长**, 你需要了解创建组织和创建 Repo, 还要掌握基本的代码提交和代码审查;

如果你是**团队成员**, 可以跳过创建组织和创建仓库步骤, **直接跳到团队协作部分**.

### 创建组织

1. 当你需要与团队进行团队协作时, 你可以在 GitHub 首页, 选择 `New organization` 新建一个组织.

![](https://pic4.zhimg.com/80/v2-a36c03df37dab6cbadc48944ecd0f273_720w.png)

2. 选择一个收费计划, 实际上, 对于小团队来说, 免费的 Free 计划已经完全足够.

![](https://pic4.zhimg.com/80/v2-8adc58be1dcf368492a2fd9fe986d8a3_720w.png)

3. 输入你们组织的名称, 联系邮件, 确认, 就可以创建一个你自己的组织了.

![](https://pic4.zhimg.com/80/v2-675dde6e0274b55d6ad649819172f72b_720w.png)

4. 再输入你要邀请的成员的用户名或者邮箱.

![](https://pic3.zhimg.com/80/v2-c288e75e28a520649b768aecd432f752_720w.png)

5. 填写一些你即将用 GitHub 的团队协作功能做些什么的信息, 就完成了组织的创建.

![](https://pic2.zhimg.com/80/v2-ff241a2b1c82d346b67598ea9b8b8a59_720w.png)

6. 最后, 你获得了一个你自己的组织, 可以写你们组织专属的 Repo 了!

![](https://pic3.zhimg.com/80/v2-4ac863e463fab93e8c0778a9b0d0acde_720w.png)

### 创建仓库

创建一个你们团队的仓库:

![](https://pic2.zhimg.com/80/v2-c2f6e1fc5216a661c3d34877aeb777a5_720w.png)

默认来说, 组织的普通成员对 Repo 访问权限是只读, 即有浏览代码的权限, 没有修改的权限. 这样的权限管理是比较推荐的, 普通成员可以通过 Pull Request 来提交自己的代码, 团队所有者可以进行代码检查, 以防止出现不好的代码.

但是如果你一定要修改权限, 也可以在组织的 `Setting` 中, 将团队成员的权限改为 `Write`.

![](https://pic2.zhimg.com/80/v2-57a17fded860de863235be798ef59c3d_720w.png)

### 团队协作

1. 队长创建 dev 分支, 方便后续合并代码, 可选.

![](https://pic4.zhimg.com/80/v2-5dd380866cfe2ff5cb22d99a76cb0efb_720w.png)

2. 在当前 Fork 一个新 Repo 到你自己的账户.

![](https://pic3.zhimg.com/80/v2-59c542d82e5d129b254af95bff44440e_720w.png)

3. 克隆你自己的新 Repo 到本地.

``` sh
git clone git@github.com:<Your-name>/Team-Test.git
cd Team-Test
```

4. 和团队同步.

使用命令

``` sh
git remote -v
```

查看有没有 upstream, 如下图即是没有.

![](https://pic3.zhimg.com/80/v2-5980f789ec90f2eb529a77223d4ad5de_720w.png)

再输入命令

``` sh
git remote add upstream git@github.com:<Team-name>/Team-Test.git
git remote -v
```

如图, 即加入成功了.

![](https://pic2.zhimg.com/80/v2-824820b5362268cb178431118d58aa25_720w.png)

使用命令与 upstream 同步:

``` sh
git fetch upstream
git merge upstream/main
```

如果遇到代码冲突, 请处理冲突.

5. 使用 push 推送到自己的 Repo

再在本地进行一些代码修改(记得 `git commit`), 然后使用

``` sh
git push
```

推送到自己的 Repo 里.

![](https://pic1.zhimg.com/80/v2-932e6bc2d878f92f591e6127ab86f884_720w.png)

6. 进行 Pull Request 合并到团队项目

在你自己 Fork 的 Repo 里发起 Pull Request:

![](https://pic4.zhimg.com/80/v2-c7ef3497f26f7b90be0281fad6fe5f37_720w.png)

![](https://pic1.zhimg.com/80/v2-259021e946665479b6f61afdbfa9ef98_720w.png)

![](https://pic4.zhimg.com/80/v2-409eefafb4dfad6b2f5d698467113fcf_720w.png)

然后项目管理者就可以对代码进行 Merge.

![](https://pic2.zhimg.com/80/v2-765e042c447c3c2a3d6a4eb44733a48d_720w.png)

于是 README.md 文件就被更新了!

![](https://pic1.zhimg.com/80/v2-2736ca012ec15142cebda716baa3bb1c_720w.png)


### 解决冲突

如果有其他人在主 Repo 做了某些修改, 你必须要同步这些修改.

例如, 原来是 `A test for team` 的文本现在变成了 `A test repo for team`.

![](https://pic2.zhimg.com/80/v2-d6098a9e3ca0d991b8cb4afda0ab6985_720w.png)

这时候, 你 Fork 的 Repo 和你电脑本地的的仓库也应该及时更新与解决冲突.

这时候, 你在你本地执行这三条命令, 处理冲突和更新代码.

``` sh
git fetch upstream
git merge upstream/main
git push
```

![](https://pic2.zhimg.com/80/v2-b1c77bae9b902cc6f01dbee14cd5d685_720w.png)

于是, 你的代码也被更新了, 恭喜, 你学会了团队协作的大部分流程了!

## 版权声明

自由转载-标注作者-禁止商用-允许衍生 ([CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/deed.zh))
