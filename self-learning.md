
## git使用方法
### 切换本地分支
`git checkout <branch-name>`
### 本地内容提交到指定的远端分支
`git push -u origin master:main` 含义是指定提交的远端仓库为origin，并将本地的master分支内容提交到远端的main分支中, 如果不指定远端分支名称则会提交到远端仓库总与本地分支同名的远端分支中