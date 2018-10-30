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
#### 创建并切换到本地分支 [参考来源](https://git-scm.com/book/zh/v1/Git-%E5%88%86%E6%94%AF-%E5%88%86%E6%94%AF%E7%9A%84%E6%96%B0%E5%BB%BA%E4%B8%8E%E5%90%88%E5%B9%B6)

	git checkout -b [分支名称]
#### 创建分支
    
    git branch [分支名称]
#### 切换到分支

    git checkout [已创建好的分支名称]
#### 显示本地分支

	git branch [-a(-a参数是显示本地仓库和远端仓库的所有分支)] 
#### 删除本地分支

	git branch [-d] [分支名称]
#### 删除远端分支

	git push origin :[分支名称](例如:dev)
