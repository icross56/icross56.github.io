git push -u origin feature_branch_name

# merge
git checkout master
git pull origin master
git merge test
git push origin master

#fetch remote branch
git branch -r 
git fetch origin remote_branch

#pull
#提交本地test分支 作为 远程的master分支
$ git push origin test:master         
#提交本地test分支作为远程的test分支

$ git push origin test:test           

#要关联一个远程库，使用命令
git remote add origin git@server-name:path/repo-name.git；

#关联后，使用命令
git push -u origin master 第一次推送master分支的所有内容；

此后，每次本地提交后，只要有必要，就可以使用命令git push origin master推送最新修改；

查看分支：git branch

创建分支：git branch <name>

切换分支：git checkout <name>

创建+切换分支：git checkout -b <name>

合并某分支到当前分支：git merge <name>

删除分支：git branch -d <name>

HEAD指向的版本就是当前版本，因此，Git允许我们在版本的历史之间穿梭，使用命令
git reset --hard commit_id。

穿梭前，用git log可以查看提交历史，以便确定要回退到哪个版本。

要重返未来，用git reflog查看命令历史，以便确定要回到未来的哪个版本。

