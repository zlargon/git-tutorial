# 遠端篇

#### [新增專案](new_project.md)

    ssh-keygen -t rsa
    ssh -T git@github.com

#### [設定 Repo URL](remote.md)

    git remote -v
    git remote add <short name> <repo url>
    git remote rm <short name>
    git remote rename <short name> <new name>

#### [上傳分支](push.md)

    git branch -a
    git push <remote name> <branch name>

#### [設定 Upstream](upstream.md)

    git push -u <remote name> <branch name>
    git branch -u <remote>/<remote branch>
    git branch --unset-upstream

#### [複製 / 下載專案](clone.md)

    git clone <repo URL>
    git clone <repo URL> -b <branch name>
    git clone <repo URL> <folder name/path>
    git clone <local project>

#### [同步遠端分支](sync.md)

    git fetch <remote name>
    git fetch --all
    git remote update
    git pull
    git pull --rebase

#### [強制更新遠端分支](force_update.md)

    git push -f

#### [刪除遠端分支](delete_branch.md)

    git push <remote name> :<branch name>
    git remote show <remote name>
    git remote prune <remote name>
    git remote update -p
    git fetch --all -p
    git fetch -p

<br><br><br>
