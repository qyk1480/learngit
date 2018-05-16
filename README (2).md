mkdir Mygit2

git diff

jk  fb（一页）  du（半页）  gG（开始结尾）  移动  5g（第5行）
/print
?print  搜索   nN
h帮助
q退出

git diff 快照ID1 快照ID2

git diff 快照ID  （当前工作目录和ID）
git diff （工作目录和暂存）
git diff HEAD （工作目录和提交）

git diff --cached ID  （暂存和ID）
git diff --cached （暂存和提交）


git commit --amend

错删 git checkout -- README.md

git rm yellow.jpg  删除  
git reset --soft HEAD~

git rm --cached filename (只删除暂存区域文件)

git mv game.py wordgame.py (重命名) 