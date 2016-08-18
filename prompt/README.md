[这是一个全面的Markdown语法](http://wowubuntu.com/markdown/)

[简书：常用语法](http://www.jianshu.com/p/q81RER)

一些简单的命令就不多说了

版本回退：<br>
**git reset --hard HEAD~xx** (如果上一次版本存在未被commit的改动，会退回去后是直接覆盖，是回退版本，而不是回退change)

**git reset --hard** (查看最新版本 也就是回退到最新版本 而你此时一个文件夹内add 但没有commit 的内容会被覆盖掉 但是你的本地仓库可以`Ctrl+z`啊)

**git reset HEAD file**(把暂存区的修改撤销 可以用diff查看)<br>
另外git reset 有三个参数
    `hard` all 全部回退 小心使用
    `soft`(当对最新的提交说明或者提交的更改不满意时，撤销最新的提交以便重新提交)
    `mixed(default)` 只有工作区不改变

**git diff**(查看工作库和最新版本库的区别)

**git rm/rm** （一个是从暂存中删除，用checkout回不去/另一个checkout可以还原）

**git clone git@github.com:xxxxx/reponame.git** （从远端克隆一个库到本地）

**git commit --amend** (比如你提交完了发现还需要做几个修改，或修改提交信息(--amend -m"需要修改的提交信息")。想要撤消刚才的提交操作，可以使用 --amend 重新提交)

**git pull**(取回远程主机某个分支的更新，再与本地的指定分支合并  git pull --rebase origin master )当时md文件和本地不再同一目录下时就是用的这个  结果自己的修改没了 都是远端没有修改的 建议先fetch

**git push**

**git rebase**(合并之后，由于之前有一次推送，因此会出现本地与远程分支不一样的情况，远端超前提交  这时候`git push origin master -f` 强调一下 真的很爽 )

**git merge** -no-ff ???

**git fetch** (现从远程origin取回最新代码 然后merge 然后一个个解决冲突 continue)

****

暂时先明白这些满足需求，命令下的细节要用的时候再看吧
