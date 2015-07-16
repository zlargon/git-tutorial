# 分支管理

#### [查看分支](show.md)

    git branch
    gitk --all &

#### [建立 / 刪除分支](create_delete.md)

    git branch <new branch name>
    git checkout <branch name>
    git checkout -b <new branch name>
    git branch -f <branch name> <commit id>
    git branch -D <branch name>
    git log <branch name>

#### [Commit Tree](commit_tree.md)

    git checkout <commit id>
    git checkout -b <new branch name> <commit id>

#### [Rebase 合併分支](rebase.md)

    git cherry-pick <commit 1> <commit 2> ...
    git rebase <new base>
    git rebase <new base> <branch name>
    git reset --hard ORIG_HEAD

#### [Merge 合併分支](merge.md)

    git merge <branch name>
    git merge --no-ff <branch name>

<br><br><br>
