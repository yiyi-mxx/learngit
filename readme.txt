git init //创建版本库
git add <file> //把文件加入暂存区
git commit -m <message>//把文件加入工作区
git status //查看仓库状态
git diff //查看仓库的改变
git log//查看仓库提交历史
git reflog //查看命令历史
git reset --hard commit_id//在版本的历史之间穿梭
git checkout --file//丢弃工作区的修改
rm test.txt//删除文件可以commit一下确定从版本库中删除该文件
git remote add origin git@github.com:yiyi-mxx/learngit.git//连接远程仓库
git push -u origin master//把本地库的内容推送到远程库
遇到问题：Warning: Permanently added 'gitee.com,120.55.226.24' (ECDSA) to the list of known hosts.
$ ssh-keygen -t rsa -C "your@email.com"
请直接按下回车
然后系统会自动在.ssh文件夹下生成两个文件，id_rsa和id_rsa.pub，用记事本打开id_rsa.pub
ssh添加一个新的ssh钥匙
git clone git@github.com:yiyi-mxx/gitskills.git//克隆远程库
git branch dev//创建分支
git chackout dev//切换分支
git branch -b dev//合并上面两个命令
git branch//列出所有分支
head都是指向当前的工作区，如果你切换到dev分支，head就指向dev
git merge dev//合并分支到master
git branch -d dev//删除分支
新版本使用 git switch -c dev//创建并切换分支
git switch master//切换分区
mmmmmm

