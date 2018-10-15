# git命令学习
===

克隆仓库
---

	git clone [仓库地址]
添加文件到暂存区
---

	git add *
_提交修改到HEAD_
	git commit -m '本次提交的注释'
_推送本次提交到远端仓库_
	git push origin [分支名称](例如:master)
_查看所有提交日志_
	git log
_为当前提交添加标签(也就是发行版本)
	git tag [标签名称] [运行 git log 命令得到的当前版本的id前10位或者8位等]
_更新远端仓库代码到本地仓库_
	git pull origin [分支名称](例如:master)
_创建本地分支_
	git checkout [分支名称]
_显示本地分支_
	git branch [-a(-a参数是显示本地仓库和远端仓库的所有分支)] 
_删除本地分支_
	git branch [-d] [分支名称]
_删除远端分支_
	git push origin :[分支名称](例如:dev)
