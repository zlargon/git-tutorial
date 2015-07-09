# Patch 管理

#### [基本觀念](basic.md)

    git log --pretty=raw

#### [關鍵字 HEAD](head.md)

    git show HEAD^
    git show HEAD~3

#### [Reset Patch](reset.md)

    git log --oneline
    git reset HEAD^
    git reset --hard HEAD^
    git reset --hard <commit id>

#### [找回消失的 Patch](reflog.md)

    git reflog
    git log -g
