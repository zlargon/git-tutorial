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

#### [修改 / 訂正 Patch](amend.md)

    git commit --amend
    git commit --amend -m <message>
    git reset --soft HEAD^
    git reset --soft HEAD@{1}           # 保命技

#### [移除單一個 Patch](remove.md)

    git cherry-pick <commit id>

#### [Rebase 互動模式](rebase_interactive.md)

    git rebase -i <after this commit>

#### [Cherry-Pick 版本衝突](cherry_pick_conflict.md)

    git cherry-pick --continue
    git cherry-pick --abort

#### [Rebase 版本衝突](rebase_conflict.md)

    git rebase --continue
    git rebase --skip
    git rebase --abort

#### [Revert Patch](revert.md)

    git revert <commit id>
    git revert --continue
    git revert --abort
