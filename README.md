# 2071用来练习的repo
## 1. 创建初始化好的主线
## 2. 分成两个项目组进行工作

 - left branch
 - right branch

    1. git fetch(获取远端最新的分支状态)
    2. git checkout -b 本地名 origin/远端名字

        `git checkout -b left origin/left`

    在各自项目组的分支上，先创建一个项目组名称的文件夹，然后在这个文件夹里面创建自己用户名的文件夹，然后在自己用户名的文件夹里面新增一个文件，文件里面随便写点东西。

    再把改动push到远端

## 3. 合并到主线(master)

    在master分支上merge其他分支(将其他分支merge到master分支)

    1. 切换到本地的master分支

        `git checkout master`
    
    2. merge

        `git merge origin/left`

## 4. 分支的创建和合并

> - 在left和right分支基础上创建各自用户名的分支
>   - 创建本地分支
>
>       `git checkout -b 本地分支的名字`
>
>   - 将这个本地分支推送到远端(创建远端分支)
>       
>       `git push -u origin/远端分支的名字`
>
