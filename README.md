This is a demo project to familiarize new employees with our software development guideline, explicitly, git/GitLab for now.
 
All new employees should demonstrate they are able to follow the steps below by themselves.

Steps
------------
1. Install client for GitLab, regardless of git on Linux, GitBash on Windows.
2. Ask manager to grant access to join a specific repo, for instance, *crashburn*.
3. Pull all files from the repo.

下载Git客户�?

初始化操�?
------------
    $ git config --global user.name <name> #设置提交者名�?
    $ git config --global user.email <email> #设置提交者邮�?
    $ git config --list #检查已有的配置信息

检出仓�?
------------
    $ git clone </path/to/repository> #克隆远端服务器上的仓�?
    
加载添加、修改、删除和重命名等操作
------------
    $ git add * #添加所有改动过的文�?
    $ git add <filename> #添加指定的文�?
    $ git rm <filename> #删除文件
    $ git mv <old> <new> #文件重命�?

提交操作
------------
    $ git commit -m <filename> #提交指定文件
    $ git commit -m “commit message�? #提交所有更新过的文�?
    $ git commit -amend #修改最后一次提�?
    $ git commit -C HEAD -a -amend #增补提交（不会产生新的提交历史纪录）

查看提交历史
------------
    $ git log #查看提交历史
    $ git log -p <file> #查看指定文件的提交历�?
    $ git blame <file> #以列表方式查看指定文件的提交历史
    $ gitk #查看当前分支历史纪录
    $ gitk <branch> #查看某分支历史纪�?
    $ gitk --all #查看所有分支历史纪�?
    $ git branch -v #每个分支最后的提交
    $ git status #查看当前状�?
    $ git diff #查看变更内容

撤消操作
------------
    $ git reset -hard HEAD #撤消工作目录中所有未提交文件的修改内�?
    $ git checkout HEAD <file1> <file2> #撤消指定的未提交文件的修改内�?
    $ git checkout HEAD. #撤消所有文�?
    $ git revert <commit> #撤消指定的提�?
    
远端操作
------------
    $ git remote -v #查看远程版本库信�?
    $ git remote show <remote> #查看指定远程版本库信�?
    $ git remote add <remote> <url> #添加远程版本�?
    $ git fetch <remote> #从远程库获取代码
    $ git pull <remote> <branch> #下载代码及快速合�?
    $ git push <remote> <branch> #上传代码及快速合�?
    $ git push <remote> : <branch>/<tagname> #删除远程分支或标�?
    $ git push -tags #上传所有标�?


更多请参见随附的github-git-cheat-sheet.pdf