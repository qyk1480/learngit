D:
cd Mygit
git init  #创建

git add README.md
git commit -m "add a readme file"



将工作目录的文件放到Git仓库：
-git add 文件名
-git commit -m "做了什么"

1修改 modified
2暂存 staged
3提交 committed

add   commit
checkout   reset

git status

git add LICENSE

git reset HEAD~ #返回上一次
git reset HEAD~5
git add LICENSE
git commit -m "add a LICENSE file"

git log #查看历史

git reset --mixed HEAD~
1移动HEAD的指向，将其指向上一个快照
2将HEAD移动后指向的快照回滚到暂存区域

git reset --soft HEAD~ 
移动HEAD的指向，将其指向上一个快照

git reset --hard HEAD~ 
1移动HEAD的指向，将其指向上一个快照
2将HEAD移动后指向的快照回滚到暂存区域
3将暂存区域的文件还原到工作目录


git reset 指定hash
git reset 版本快照 文件名/路径

git reset --hard hash值