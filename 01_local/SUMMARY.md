# 本機篇

## _本章節講的所有指令，皆是在本機端離線操作；也就是說，完全不需要透過網路來操作_

#### [建立 Git 專案](create_project.md)

	- git init

#### [提交一個 Patch](commit_a_patch.md)

	- git status
	- git add <file>
	- git commit
	- git log
	- git show

#### [新增 / 修改檔案](modify_files.md)

    - git diff
    - git diff <file>
    - git diff --cached
    - git add -A
    - git commit -m <message>
    - git show <commit_id>

#### [刪除檔案](remove_files.md)

    - git rm <file>
    - git add -u

### 移除 patch (3)
* [reset](reset.md)
* [revert](revert.md)
* [reflog](reflog.md)

### branch 相關指令 (3)
* [branch](branch.md)
* [checkout](checkout.md)
* [cherry-pick](cherry-pick.md)

### 合併 branch (2)
* [merge](merge.md)
* [rebase](rebase.md)
