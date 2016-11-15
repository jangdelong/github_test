---
title: Github 使用教程
categories:
  - Web技术
author: Jelon
tags:
	- Github
	- Git
thumbnail: http://7xs305.com1.z0.glb.clouddn.com/github_tutorial/5.png
blogexcerpt: 很多时候，我们想把自己做的开源项目放到 Github 上面，但是不会用Github，怎么办？没关系，Github 使用教程网上一大堆，随便一搜到处都是。尽管如此，如果你不嫌弃的话，你也可以看看下面教程，以下是我自己使用 github 过程中，总结的一些 Github 使用步骤，这里给大家安利以下...

---

很多时候，我们想把自己做的开源项目放到 Github 上面，但是不会用Github，怎么办？没关系，Github 使用教程网上一大堆，随便一搜到处都是。尽管如此，如果你不嫌弃的话，你也可以看看下面教程，以下是我自己使用 github 过程中，总结的一些 Github 使用步骤，这里给大家安利一下。

### 一、创建本地 git 仓库

使用 `cd` 切换到你本地项目的目录（可以手动去创建一个目录，例如 /gitbub_test），然后执行以下 git 命令

```bash
git init
```

![创建本地 git 仓库](http://7xs305.com1.z0.glb.clouddn.com/github_tutorial/1.png)

### 二、将项目文件添加至你的 git 仓库

将你的项目文件拷贝到刚才创建的目录下，然后执行以下 git 命令

```bash
git add . # 添加所以修改过的文件或者新文件
```

### 三、将 add 的文件 commit 到仓库

将刚才已经添加的文件 commit 到仓库，执行命令如下

```bash
git commit -m '这是注释语句'
```
![commit 到仓库](http://7xs305.com1.z0.glb.clouddn.com/github_tutorial/3.png)

### 四、去 github 上创建 Repository，截图如下

创建页面如下：

![创建页面截图](http://7xs305.com1.z0.glb.clouddn.com/github_tutorial/2.png)

创建完成之后结果如下：

![](http://7xs305.com1.z0.glb.clouddn.com/github_tutorial/6.png)

### 五、将本地仓库关联至 github

github Repository 创建好之后，接下来就是如何将本地 git 仓库关联至 github ，执行以下 git 命令即可

```bash
git remote add origin https://github.com/jangdelong/github_test.git
```

![关联仓库至 github](http://7xs305.com1.z0.glb.clouddn.com/github_tutorial/4.png)

### 六、将 github 上的代码拉去到本地

执行以下 git 命令可将 github 上原有的代码拉去到本地。这一步前提是你的 github 上原来已经存在代码或文件，否则这一步可以省去。

```bash
git pull origin master
```

### 七、提交代码

最后一步就是提交代码了，执行 git 命令如下

```bash
git push -u origin master
```

这样，我们在 github 上就可以看到我们的项目代码了。

![完成](http://7xs305.com1.z0.glb.clouddn.com/github_tutorial/5.png)









