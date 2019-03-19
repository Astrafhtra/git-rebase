q 退出该命令
git add 提交到工作区
git commit -m 提交到暂存区
git checkout -b banch1 检查分支

# git rebase
让我们的提交记录更干净，有很多人一起开发

基点  在新建分支时产生的  提交记录的分叉
git add 1 2          提交1 2
git log oneline      一行列出
git checkout -b "branch1"  创建一个新的分支branch1
git checkout master  返回master分支
git add 3 4 提交3 4
git checkout branch1  返回 branch1分支
git add 5 6  提交5 6
git log --oneline --graph 一行列出
git merge branch1
git  --oneline --graph  列出合并分支
git reset --hard HEAD^  返回合并分支之前
git checkout branch1    返回branch1分支
git rebase master       移动基点到master分支后  即是5 6 接到4后面
git checkout master     返回master
git merge branch1
git log --oneline --graph 列出


