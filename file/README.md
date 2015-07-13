# 檔案管理

#### [新增 / 修改檔案](modify.md)

    git diff
    git diff <file>
    git diff --cached
    git add -A
    git commit -m <message>
    git show <commit_id>

#### [刪除檔案](remove.md)

    git rm <file>
    git add -u

#### [搬移檔案](move.md)

    git mv <file> <directory>

#### [重新命名檔案](rename_files.md)

    git mv <file> <new_name>

#### [檔案狀態](status.md)

    git reset HEAD
    git reset HEAD <file>
    git checkout -- <file>

#### [檔案還原](recover.md)

    git checkout -- <file>
    git reset HEAD
    git reset HEAD <file>
    git reset --hard HEAD
