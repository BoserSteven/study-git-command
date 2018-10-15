git命令学习
===

#### 克隆仓库

	git clone [仓库地址]
#### 添加文件到暂存区

	git add *
#### 提交修改到HEAD

	git commit -m '本次提交的注释'
#### 推送本次提交到远端仓库

	git push origin [分支名称](例如:master)
#### 查看所有提交日志

	git log
#### 为当前提交添加标签(也就是发行版本)

	git tag [标签名称] [运行 git log 命令得到的当前版本的id前10位或者8位等]
#### 更新远端仓库代码到本地仓库

	git pull origin [分支名称](例如:master)
#### 创建本地分支

	git checkout [分支名称]
#### 显示本地分支

	git branch [-a(-a参数是显示本地仓库和远端仓库的所有分支)] 
#### 删除本地分支

	git branch [-d] [分支名称]
#### 删除远端分支

	git push origin :[分支名称](例如:dev)
