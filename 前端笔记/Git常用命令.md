# git 常用命令

git config --global user.name 用户名 ：设置用户签名；

git config --global user.email 邮箱 ：设置用户签名； 

git init :初始化本地库； 

git status :查看本地库状态； 

git add 文件名 ：添加到暂存库； 

git commit -m“日志信息” 文件名 ：提交到本地库； 

git reflog :查看历史记录； 

git reset --hard 版本号 ：版本穿梭；

# git 分支操作

git branch 分支名 ：创建分支；

 git branch -v : 查看分支； git checkout 分支名 ：切换分支； 

git merge 分支名 :将指定的分支合并到当前分支上；

# github远程库

git remote -v :常看当前所有远程地址别名； 

git remote add 别名 远程地址 ：添加别名； 

git push 别名 分支 ：推送分支到远程库；

git pull 别名 分支 ：拉去分支到本地库； 

git clone 远程地址 ：克隆远程库分支到本地（第三者）（拉取代码，初始化本地 库，创建别名）；

# github远程库免密登录

ssh-keygen -t rsa -C [2807650679@qq.com](mailto:2807650679@qq.com) #添加ssh文件