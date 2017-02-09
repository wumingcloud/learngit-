# this is my first git repository!

## git command with notes
>http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000

- git config --list
- git config --global user.name "xxx"
- git config --global user.email "xxx@xxx"

- git init 
创建仓库

- git add 
添加新的需要跟踪的文件到仓库，或者更新状态

- git commit -m "xxxxxx" 
提交更新

- git status 
查看仓库状态

- git diff 
查看文件改动状态

- git log 
查看仓库改动日志
- git log --pretty=oneline

- git reflog 
查看仓库改动情况

- git reset --hard commit_id 
HEAD 指向当前版本 HEAD^ 回到上一个版本 HEAD~100 表示 回到前100个版本

- git checkout -- file
丢弃工作区的修改
恢复file到版本库中的状态

- git reset HEAD file 
丢弃暂存区的修改，此时仅含有工作区的修改

- git rm file
从版本库中删除file，记得commit

- git remote add origin git@server-name:path/repo-name.git；
关联一个远程库

- git push -u origin master
关联后，使用命令第一次推送master分支的所有内容；
- git push origin master
将本地master分支推送到github

- git clone git@github.com:username/repo-name.git
克隆仓库到本地

- git branch
查看分支

- git branch <name>
创建分支：

- git checkout <name>
切换分支：

- git checkout -b <name>
创建+切换分支

- git merge <name>
合并某分支到当前分支

- git branch -d <name>
删除分支

- git log --graph --pretty=oneline --abbrev-commit
以图形式查看仓库日志

- git merge --no-ff -m "xx" dev
将合并作为一次commit记录

# just for test
#####