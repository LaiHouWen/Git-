# Git-
Git工具及使用

Git常用的一些命令

1.从远程服务器中克隆一份代码到本地
$ git clone git@github.com:xxxxx/xxxx.git

2.本地的代码同步远程仓库的代码
$ git remote add origin git@192.168.1.119:ndshow
$ git push origin master 将文件给推到服务器上 

$ git remote show origin 显示远程库origin里的资源 

3. 查看本地所有分支 
$ git branch [-a]

4.查看远程的所有分支 
$ git branch -r

5.提交并且加注释 
$ git commit -m "xxxx"

6.将本地库与服务器上的库进行关联 
$ git push origin master:xxxxx

7.切换到本地dev分支
$ git checkout xxxx

8.查看远程库
$ git remote show 

9.切换到远程dev分支
$ git checkout --track origin/dev 

10. 看你commit的日志
$ git log

11.本地与服务器端同步
$ git pull

12. 从主分支master创建branch_0.1分支
$ git branch branch_0.1 master

13. 将branch_0.1重命名为branch_1.0
$ git branch -m branch_0.1 branch_1.0

14.切换到branch_1.0/master分支
$ git checkout branch_1.0/master 

15.将本地代码推送到远程仓库
$ git push origin master



