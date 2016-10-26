git is good
Git is a distributed version control system.
Git is free software.
Git is simple
Git tracks changes

My Stupid boss still prefers SVN

git diff HEAD -- readme.txt

你可以发现，Git会告诉你，git checkout -- file可以丢弃工作区的修改：
Git同样告诉我们，用命令git reset HEAD file可以把暂存区的修改撤销掉（unstage），重新放回工作区：

当你不知道该怎么做的时候，使用git status 。git会显示目前git的状态，并
提示你可能要进行的操作，以及命令。这个功能对新手很有用。

命令git rm用于删除一个文件。如果一个文件已经被提交到版本库，那么你永远不用担心误删，但是要小心，你只能恢复文件到最新版本，你会丢失最近一次提交后你修改的内容。

git remote 

git checkout -b dev  创建并切换到dev分支