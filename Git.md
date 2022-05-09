# Git

详细笔记在pdf中查找

安装

- 官网地址 ： https://git-scm.com/
- 查看GNU协议，可以直接点击下一步
- 安装成功后 ： git --version 查看版本信息

## 1、常用命令

| 命令名称                             | 作用           |
| ------------------------------------ | -------------- |
| git config --global user.name 用户名 | 设置用户签名   |
| git config --global user.email 邮箱  | 设置用户签名   |
| git init                             | 初始化本地库   |
| git status                           | 查看本地库状态 |
| git add 文件名                       | 添加到暂存区   |
| git commit -m "版本信息" 文件名      | 提交到本地库   |
| git reflog                           | 查看历史记录   |
| git reset --hard 版本号              | 版本切换       |

## 2、分支

| 命令名称            | 作用                         |
| ------------------- | ---------------------------- |
| git branch 分支名   | 创建分支                     |
| git branch -v       | 查看分支                     |
| git checkout 分支名 | 切换分支                     |
| git merge 分支名    | 把指定的分支合并到当前分支上 |

## 3、团队协作Github

```text
邮箱：tangzehua2022@163.com
账号:tangzehuahua
	
	aizhoujiaping@163.com
	aizhoujiaping
	
	woaijiaping2022@163.com
	woaijiaping2022
	
密码：zhou12345@na
```

| 命令名称                           | 作用                                             |
| ---------------------------------- | ------------------------------------------------ |
| git remote -v                      | 查看当前所有远程地址别名                         |
| git remote add 别名 远程地址       | 起别名                                           |
| git push 别名/远程地址  分支       | 推送本地分支上的内容到远程仓库                   |
| git clone 远程地址/别名            | 将远程仓库的内容克隆到本地                       |
| git pull 远程库地址/别名  远程分支 | 将远程仓库对于分支最新内容拉到本地与当前分支合并 |

