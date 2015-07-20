# 進階篇

#### [檔案暫存](stash.md)

    git stash
    git stash list
    git stash pop
    git stash pop stash@{n}
    git stash drop
    git stash drop stash@{n}
    git stash clear

#### [Add / Checkout 檔案部分內容](add_checkout_part_of_file.md)

    git add -p
    git checkout -p

#### [版本標籤](tag.md)

    git tag
    git tag <tag name> <commit id>
    git tag -a <tag name> <commit id>
    git tag -a <tag name> <commit id> -m <msg1> -m <msg2>
    git tag -a <tag name> <tag name>^{} -f
    git tag -d <tag name>

    git push <remote name> <tag name>
    git push <remote name> --tags
    git push <remote name> :<tag name>
    git push -f <remote name> <tag name>

<br><br><br>
