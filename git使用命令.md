# 一.参考地址

https://www.cnblogs.com/schaepher/p/5561193.html

# 二.初始化本地仓库与连接远程仓库

## （一）初始化本地仓库

```JavaScript
1.git init //初始本地仓库

2.git add . //将当前目录下的工作区的修改添加到暂存区（临时保存）

3.git commit：将暂存区的内容提交到本地仓库（永久保存）。
# 提交到本地仓库并添加描述
git commit -m "更新了 readme.md 的安装说明"

4.git push：将本地仓库的提交推送到远程仓库（如 GitHub）。
git push origin master
```

（二）连接远程仓库

```
git remote add origin https://github.com/yitiaolittle/fishlearning.git
```

