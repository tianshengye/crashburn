This is a demo project to familiarize new employees with our software development guideline, explicitly, git/GitLab for now.
 
All new employees should demonstrate they are able to follow the steps below by themselves.

Steps
------------
1. Install client for GitLab, regardless of git on Linux, GitBash on Windows.
3. Update a file.
5. Remove a file.
7. Resolve conflicts.

下载Git客户端

初始化操作
------------
    $ git config --global user.name <name> #设置提交者名字
    $ git config --global user.email <email> #设置提交者邮箱
    $ git config --list #检查已有的配置信息

检出仓库
------------
    $ git clone </path/to/repository> #克隆远端服务器上的仓库
    
加载添加、修改、删除和重命名等操作
------------
    $ git add * #添加所有改动过的文件
    $ git add <filename> #添加指定的文件
    $ git rm <filename> #删除文件
    $ git mv <old> <new> #文件重命名

提交操作
------------
    $ git commit -m <filename> #提交指定文件
    $ git commit -m “commit message” #提交所有更新过的文件
    $ git commit -amend #修改最后一次提交
    $ git commit -C HEAD -a -amend #增补提交（不会产生新的提交历史纪录）

查看提交历史
------------
    $ git log #查看提交历史
    $ git log -p <file> #查看指定文件的提交历史
    $ git blame <file> #以列表方式查看指定文件的提交历史
    $ gitk #查看当前分支历史纪录
    $ gitk <branch> #查看某分支历史纪录
    $ gitk --all #查看所有分支历史纪录
    $ git branch -v #每个分支最后的提交
    $ git status #查看当前状态
    $ git diff #查看变更内容

撤消操作
------------
    $ git reset -hard HEAD #撤消工作目录中所有未提交文件的修改内容
    $ git checkout HEAD <file1> <file2> #撤消指定的未提交文件的修改内容
    $ git checkout HEAD. #撤消所有文件
    $ git revert <commit> #撤消指定的提交
    
远端操作
------------
    $ git remote -v #查看远程版本库信息
    $ git remote show <remote> #查看指定远程版本库信息
    $ git remote add <remote> <url> #添加远程版本库
    $ git fetch <remote> #从远程库获取代码
    $ git pull <remote> <branch> #下载代码及快速合并
    $ git push <remote> <branch> #上传代码及快速合并
    $ git push <remote> : <branch>/<tagname> #删除远程分支或标签
    $ git push -tags #上传所有标签


更多请参见随附的github-git-cheat-sheet.pdf
