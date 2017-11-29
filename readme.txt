Git is a distributed version control system
Git is free software distributed under the GPL


Git learn
1.git init  初始化git仓库
2.git add <file> 
3.git commit 
4.git status
5.git diff
6.git log
7.git reflog
8.git reset --hard commit_id
9.git checkout --<file>
10.rm <file>
#关联github
git remote add origin git@github.com:touruscy/learngit.git
#推送到github
git push -u origin master
#克隆到本地
git clone add origin git@github.com:touruscy/learngit.git

git branch 查看分支
git branch<name> 创建分支
git checkout<name>切换分支
git checkout -b<name>创建+切换分支
git merge<name> 合并某分支到当前分支
git branch -d <name>删除分支
git branch -D <name>强行删除分支（分支没合并内容时强行删除）

git log --graph 可以查看分支合并图
 
git stash 隐藏工作现场，修复bug时使用
git stash pop 返回工作现场

git remote -v查看远程库信息
git push origin branch-name 本地推送分支
git pull 抓取远程新提交
git checkout -b branch-name origin/branch-name 在本地创建和远程分支对应的分支
git branch --set-upstream branch-name origin/branch-name 建立本地分支和远程分支的关联

git tag<name> 新建一个标签
git tag -a<tagname> -m "bla..." 可以指定标签信息
git tag -s<tagname> -m "bla..." 可以用PGP签名标签
git tag 查看所有的标签
