cmd
git config --global user.name "jl1480" #qyk1480
git config --global user.email "1336726254@qq.com"
git config --list  #查看是否成功

D:
cd Mygit
git init  #创建

git add README.md
git commit -m "add a readme file"



git status

git add LICENSE

git reset HEAD~ #返回上一次
git reset HEAD~5
git add LICENSE
git commit -m "add a LICENSE file"

git log #查看历史


git reset 指定hash 向前 向后
git reset 版本快照 文件名/路径

git reset --hard hash值

git branch 分支名 (创建)
git log --decorate
git checkout 分支名 (转)
git log --decorate --oneline --graph --all

git checkout master

git merge 分支名(合并)

git checkout -b 分支名(创建 转)

git branch -d 分支名(删除)

git reset --hard 分支名

git stash（保护现场）
git stash list  查看
1.git stash apply恢复，但是恢复后，stash内容并不删除，你需要用git stash drop来删除
2.git stash pop（回到现场）