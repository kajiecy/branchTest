# 查看结果
$ git status
# 对比差异
$ git diff
# 查看历史提交
$ git log
# 回退命令：
$ git reset --hard HEAD^         回退到上个版本
$ git reset --hard HEAD~3        回退到前3次提交之前，以此类推，回退到n次提交之前
$ git reset --hard commit_id     退到/进到 指定commit的sha码
# 创建一个分支：
git checkout master //进入master分支
git checkout -b frommaster //以master为源创建分支frommaster
# 删除的分支
git branch -D  要删除的分支
git push origin  --delete     要删除的远程分支


git push origin frommaster //将本地frommaster 分支作为远程frommaster 分支
