This is a demo project to familiarize new employees with our software development guideline, explicitly, git/GitLab for now.
 
All new employees should demonstrate they are able to follow the steps below by themselves.

Steps
------------
1. Install client for GitLab, regardless of git on Linux, GitBash on Windows.
2. Ask manager to grant access to join a specific repo, for instance, *crashburn*.
3. Pull all files from the repo.

ä¸è½½Gitå®¢æ·ç«?

åå§åæä½?
------------
    $ git config --global user.name <name> #è®¾ç½®æäº¤èåå­?
    $ git config --global user.email <email> #è®¾ç½®æäº¤èé®ç®?
    $ git config --list #æ£æ¥å·²æçéç½®ä¿¡æ¯

æ£åºä»åº?
------------
    $ git clone </path/to/repository> #åéè¿ç«¯æå¡å¨ä¸çä»åº?
    
å è½½æ·»å ãä¿®æ¹ãå é¤åéå½åç­æä½
------------
    $ git add * #æ·»å æææ¹å¨è¿çæä»?
    $ git add <filename> #æ·»å æå®çæä»?
    $ git rm <filename> #å é¤æä»¶
    $ git mv <old> <new> #æä»¶éå½å?

æäº¤æä½
------------
    $ git commit -m <filename> #æäº¤æå®æä»¶
    $ git commit -m âcommit messageâ? #æäº¤æææ´æ°è¿çæä»?
    $ git commit -amend #ä¿®æ¹æåä¸æ¬¡æäº?
    $ git commit -C HEAD -a -amend #å¢è¡¥æäº¤ï¼ä¸ä¼äº§çæ°çæäº¤åå²çºªå½ï¼

æ¥çæäº¤åå²
------------
    $ git log #æ¥çæäº¤åå²
    $ git log -p <file> #æ¥çæå®æä»¶çæäº¤åå?
    $ git blame <file> #ä»¥åè¡¨æ¹å¼æ¥çæå®æä»¶çæäº¤åå²
    $ gitk #æ¥çå½ååæ¯åå²çºªå½
    $ gitk <branch> #æ¥çæåæ¯åå²çºªå½?
    $ gitk --all #æ¥çææåæ¯åå²çºªå½?
    $ git branch -v #æ¯ä¸ªåæ¯æåçæäº¤
    $ git status #æ¥çå½åç¶æ?
    $ git diff #æ¥çåæ´åå®¹

æ¤æ¶æä½
------------
    $ git reset -hard HEAD #æ¤æ¶å·¥ä½ç®å½ä¸­æææªæäº¤æä»¶çä¿®æ¹åå®?
    $ git checkout HEAD <file1> <file2> #æ¤æ¶æå®çæªæäº¤æä»¶çä¿®æ¹åå®?
    $ git checkout HEAD. #æ¤æ¶æææä»?
    $ git revert <commit> #æ¤æ¶æå®çæäº?
    
è¿ç«¯æä½
------------
    $ git remote -v #æ¥çè¿ç¨çæ¬åºä¿¡æ?
    $ git remote show <remote> #æ¥çæå®è¿ç¨çæ¬åºä¿¡æ?
    $ git remote add <remote> <url> #æ·»å è¿ç¨çæ¬åº?
    $ git fetch <remote> #ä»è¿ç¨åºè·åä»£ç 
    $ git pull <remote> <branch> #ä¸è½½ä»£ç åå¿«éåå¹?
    $ git push <remote> <branch> #ä¸ä¼ ä»£ç åå¿«éåå¹?
    $ git push <remote> : <branch>/<tagname> #å é¤è¿ç¨åæ¯ææ ç­?
    $ git push -tags #ä¸ä¼ æææ ç­?


æ´å¤è¯·åè§ééçgithub-git-cheat-sheet.pdf