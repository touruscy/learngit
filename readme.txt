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

123