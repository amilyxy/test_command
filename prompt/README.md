[这是一个全面的Markdown语法](http://wowubuntu.com/markdown/)

[简书：常用语法](http://www.jianshu.com/p/q81RER)

版本回退：<br>
**git reset --hard HEAD~xx** (如果上一次版本存在未被commit的改动，会退回去后是直接覆盖，是回退版本，而不是回退change)<br>
**git reset --hard** (查看最新版本 也就是回退到最新版本 而你此时一个文件夹内add 但没有commit 的内容会被覆盖掉 但是你的本地仓库可以`Ctrl+z`啊)<br>
**git reset HEAD file**(把暂存区的修改撤销 可以用diff查看)<br>
**git diff**(查看工作库和最新版本库的区别)<br>
**git rm/rm** （一个是从暂存中删除，用checkout回不去/另一个checkout可以还原）<br>
**git clone git@github.com:xxxxx/reponame.git** （从远端克隆一个库到本地）<br>
**git commit --amend** (比如你提交完了发现还需要做几个修改，或修改提交信息(--amend -m"需要修改的提交信息")。想要撤消刚才的提交操作，可以使用 --amend 重新提交)<br>
**git pull**<br>
**git push**<br>
**git rebase**<br>
**git aquash**<br>
