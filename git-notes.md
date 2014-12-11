### Git学习笔记

####初始化git：

```
git init
```
####查看git的设置

```
git config --global --list
```

####设置git

```
git config --global user.name "your name"
git config --global user.email "you email"
```

####添加文件到版本库的索引

```
git add learningGit.md
```

####删除文件

如果本地删除后在提交到服务器，那么就彻底的删除了，所以删除要谨慎。

```
git rm test.txt
```

####提交创建一条提交记录

```
git -commit -m "your commit"
```

####推送到远程服务器

```
git push origin master
```

####取得并合并本地库

```
git pull
```

更新远程库到本地，不合并

```
git fetch
```

合并本地库

```
git merge
```

####有时候本地的无法通过上面的推送，可以使用这个强制推送。

```
git push f
```

####查看当前的状态

```
git status
```

####克隆远程版本库

```
git clone git://
```

####查看版本：

```
git --version
```
查看帮助，很多命令记不住的话，直接查看帮助了。

```
git help
```

###网站


* [Git 初學筆記 - 指令操作教學](http://blog.longwin.com.tw/2009/05/git-learn-initial-command-2009/)

* [Git简易指南](http://www.bootcss.com/p/git-guide/)

* [廖雪峰的官方网站](http://www.liaoxuefeng.com/)