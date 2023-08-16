git config --global user.name xxx
git config --global user.email xxx

ssh-keygen -t rsa -C "your_email@example.com" //创建SSH Key，把公钥添加到GitHub

.gitignore

### 4.1 基本操作

git init //初始化仓库
git status //查看仓库状态
git add //向暂存区中添加文件
git commit -m "xxx" //保存仓库的历史记录
git log //完整查看提交日志
git reflog //简要查看提交日志
git diff // 查看更改前后的差别

### 4.2 分支的操作

git branch // 显示分支一览表
git checkout -b //创建、切换分支
git merge //合并分支
git log --graph //以图表形式查看分支

### 4.3 更改提交的操作

git reset --hard 版本号 //回溯历史版本
git commit --amend //修改提交信息
git rebase -i //压缩历史

### 4.4 推送至远程仓库

git remote add //添加远程仓库
git push -u //推送至远程仓库


### 4.5 从远程仓库获取

git clone //获取远程仓库
git pull //获取最新的远程仓库分支
