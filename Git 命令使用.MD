# Git

- 查看当前所有分支 列出本地和远程

`
git branch -a
`

[描述](01-git 查看当前所有的分支.PNG)

`
(no branch, rebasing master)
master
remotes/origin/HEAD -> origin/master
remotes/origin/dev1.1.1
remotes/origin/master
remotes/origin/v2.0.1
`

- 检出分支 1 此命令去远程下载分支，下载完成之后并会自动切换到此分支

`
git checkout -b dev1.1.1 origin/dev1.1.1
`

- 检出分支 2 下面的命令会先去看本地是否有v2.0.1的分支，如果没有则会去新建一个v2.0.1的分支，如果有则会切换的v2.0.1分支

`git checkout -b v2.0.1
`
- 分支切换

`
git checkout dev1.1.1
`

- 删除分支 v2.0.1 

`git branch -D v2.0.1
`