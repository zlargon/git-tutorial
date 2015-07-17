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

<br><br><br>
