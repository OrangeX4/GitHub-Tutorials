# GitHub 简易指南

## 为什么要看这篇指南

如果你是刚刚开始学习编程的学生, 想要了解和学习如何使用 GitHub, 那么, 你找对教程了!

这就是你最应该看的 GitHub 指南.

看完这篇指南, 你将会收获:

* 对 GitHub 界面和功能的基本了解
* 版本控制工具 Git 的基础使用
* 基础的 Markdown 写作
* 你的第一个 Pull Request


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

![](https://pic3.58cdn.com.cn/nowater/webim/big/n_v21f5c5f69d4b245dea94be0de691b7412.png)

2. 紧接着, 填入你的用户名, 邮箱和密码, 再点击 `Create account`.

![](https://pic3.58cdn.com.cn/nowater/webim/big/n_v29384e1904ec4471eb47303060c320a4d.png)

3. 经过一系列选择, 验证邮箱之后, 看见这个页面, 选择 `Create a repository`, 创建你的第一个仓库.

![](https://pic3.58cdn.com.cn/nowater/webim/big/n_v2bad15e996e3648058c2509beadfb5354.png)

4. 填写仓库的名称, 介绍和其他配置.

![](https://pic3.58cdn.com.cn/nowater/webim/big/n_v22500d82278e44b26b2132c2d25718efb.png)

5. 当你看见这样的提示, 他是在提醒你进行后续操作, 恭喜你, 你的第一个代码仓库创建成功了!

![](https://pic3.58cdn.com.cn/nowater/webim/big/n_v2b8ab823040984abdb38b02c504e4bca3.png)


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

![](https://pic3.58cdn.com.cn/nowater/webim/big/n_v2d76fdf00a5ff481dbe4251ab974e04aa.png)

安装完成后, 请打开你的命令行终端, 输入命令 `git`, 回车.

(终端打开方式 Win 键, 输入 cmd, 或者 powershell, 回车)

![](https://pic3.58cdn.com.cn/nowater/webim/big/n_v2d9ff5acf817a4212925819ad8ba3537d.png)

如有如图的输出显示, 那么你就成功安装 Git 了.

### Git 使用

请参考 [廖雪峰的 Git 教程](https://www.liaoxuefeng.com/wiki/896043488029600).

你不需要非常认真地将其全部记住, 只需要简单地浏览, 知道 Git 有些什么功能, 再将其当作工具书, 需要时再翻看即可.

最基本, 你也需要掌握 Git 的这些内容:

![](https://pic3.58cdn.com.cn/nowater/webim/big/n_v2432a1e69eee44062aa343c1a539b6fcd.png)

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

![](https://pic3.58cdn.com.cn/nowater/webim/big/n_v21b24b30897854c1d8c525f064cd84366.png)


## GitHub 文档

不出所料的话, 你已经在 GitHub 成功创建了自己的第一个代码仓库了.

接下来, 你要给你的仓库加一些介绍文档: `README.md`.

如图, 在 GitHub 新建 Repo 后, 照着 GitHub 的说明执行:

![](https://pic3.58cdn.com.cn/nowater/webim/big/n_v297247b20bab6413a847b1226858d8262.png)

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

![](https://pic3.58cdn.com.cn/nowater/webim/big/n_v218a5ced047d142909883f35e9013d7c4.png)

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

> ``` python
> print("Hello, World!")
> ```

请将前面的 '>' 去掉, 这是不需要的.

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

![](https://pic3.58cdn.com.cn/nowater/webim/big/n_v2fdfd03c736ce41f59b62163c5994f32b.png)

### Issues 页面

![](https://pic3.58cdn.com.cn/nowater/webim/big/n_v208a5e92318754a7ab068f82ea75b131e.png)

### Pull requests 页面

![](https://pic3.58cdn.com.cn/nowater/webim/big/n_v2fbd27d6535b04d298de996e85b427e64.png)

一般来说, Pull Request 的流程是:
1. 先 Fork 这个 Repo, 你就有了这个 Repo 的一个专属你的复制版 Repo;
2. 用 Git Clone 克隆到本地, 进行你想进行的代码修改;
3. Git Push 到你的复制版远程仓库;
4. 提一个 Pull Request 给原来的 Repo.

整个流程会在后续详细说明, 你可以体验到你的第一个 Pull Request.


## 实战! 提交你的第一个 Pull Request

未完待续...
