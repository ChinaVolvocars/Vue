# Vue
# Git

- 查看当前所有分支 列出本地和远程

`
git branch -a
`

![查看当前所有分支](https://github.com/ChinaVolvocars/Vue/blob/master/01-git%20%E6%9F%A5%E7%9C%8B%E5%BD%93%E5%89%8D%E6%89%80%E6%9C%89%E7%9A%84%E5%88%86%E6%94%AF.PNG)


- 检出分支 1 此命令去远程下载分支，下载完成之后并会自动切换到此分支

`
git checkout -b dev1.1.1 origin/dev1.1.1
`

![检出分支](https://github.com/ChinaVolvocars/Vue/blob/master/02-git%20%E6%A3%80%E5%87%BA%E8%BF%9C%E7%A8%8B%E5%88%86%E6%94%AF.PNG)


- 检出分支 2 下面的命令会先去看本地是否有v2.0.1的分支，如果没有则会去新建一个v2.0.1的分支，如果有则会切换的v2.0.1分支

`git checkout -b v2.0.1
`

![检出分支](https://github.com/ChinaVolvocars/Vue/blob/master/02-git%20%E6%A3%80%E5%87%BA%E5%88%86%E6%94%AF.PNG)


- 分支切换

`
git checkout master
`

![分支切换](https://github.com/ChinaVolvocars/Vue/blob/master/01-git%20%E5%88%86%E6%94%AF%E5%88%87%E6%8D%A2.PNG)


- 删除分支 v2.0.1 

`git branch -D v2.0.1
`

![删除分支](https://github.com/ChinaVolvocars/Vue/blob/master/%E5%88%A0%E9%99%A4%E6%9C%AC%E5%9C%B0%E5%88%86%E6%94%AF.PNG)
