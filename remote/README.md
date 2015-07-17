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

#### [強制更新遠端分支](force_update.md)

    git push -f

<br><br><br>
