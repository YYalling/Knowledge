# 正常使用
1. 建立信息
   * git config --global user.email **email**
   * git config --global user.name **name**
2. 初始化
    * git init 
    * git clone **URL**
3. 添加到暂存区
    * git add .
4. 提交修改
    * git commit -m **"tips"**
5. 添加远程仓库
    * git remote add origin **URL**
6. 推送远程仓库
    * git push origin master

# 命令

## 创建选择分支
* git branch **name** :创建一个分支
* git checkout **name** :选择一个分支
* git switch **name** :选择一个分支(新指令)
* git checkout -b **name** :创建一个分支并选择此分支


## 分支的合并
* git merge **name** :name分支合并到当前选中分支
* git rebase **name**：当前分支作为副本保留，并将当前分支作为name分支的子文件存在
![rebase解释](./Picture/git%20rebase.png)

## 其他
* git status:查看当前文件状态
* git log:查看提交版本及版本号
* git reset --hard **版本号**：回退到指定的版本
* git reflog :全部的提交信息

## 远程仓库
* git remote add origin **URL** ：将远程仓库命名为origin并记录
* git push origin master:推送到远程仓库的master分支
    * git branch dev： 创建一个dev分支
    * git checkout dev：切换到dev分支
    * git pull origin dev ：把远程存储仓库中的dev分支更新到现在的dev分支中，此时就是我们正在开发的代码啦