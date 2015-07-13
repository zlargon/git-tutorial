# 重新命名檔案

在前一個章節有提到，搬移檔案的操作對 git 而言，也可以看成是一種 "重新命名" 的概念

> 事實上，並不只有是 git，`Unix` 上的 `mv` 也是把 "搬移" 跟 "重新命名" 視為相同的概念

<br>

## 使用 `git mv <file> <new_name>` 來重新命名檔案

|  | Command Format | Introduction |
| --- | --- | --- |
| ___Move___ | <code>git mv &lt;file&gt; __&lt;directory&gt;__</code> | 把檔案移到某個資料夾底下 |
| ___Rename___ | <code>git mv &lt;file&gt; __&lt;new_name&gt;__</code> | 把檔案重新命名為 ...<br>（移到 "同一個資料夾" 底下成為 xxx 檔案）|


<br>

我們現在將剛才 `my_folder` 底下的 `numbers.txt` 移回原目錄底下，並且重新命名成 `num.txt`

```
$ git mv my_folder/numbers.txt .
$ git mv numbers.txt num.txt
```

![git move and rename file](rename/git_mv.png)

我們透過 `ls` 可以看出，`numbers.txt` 確實已經被重新命名為 `num.txt` 了

<br>

提交 patch，並用 `git show` 來查看這次提交所修改的內容

```
$ git commit -m "Rename numbers.txt to num.txt"
$ git show
```

![git commit and git show](rename/git_show.png)

<br>

## git 會自動忽略空資料夾

現在我們透過 `ls` 可以看出，現在目錄下有一個 `my_folder/` 的空資料夾，與一個 `num.txt` 的檔案

既然 `my_folder/` 已經用不到了，那麼我們就把他移除，並用 `git status` 來查看狀態

```
$ rm -rf my_folder/
$ git status
```

![git ignore empty folder](rename/ignore_empty_folder.png)

雖然我們已經把 `my_folder` 刪掉了，可是 `git status` 卻沒有發生任何的狀態改變？

這是因為這些空資料夾對於整個 project 來說，本身可有可無

因此 git 認為，既然資料夾裡面沒有任何東西，那麼就沒有必要去在意他的存在

git 唯一在意的是檔案的內容

而資料夾本身並不是一個檔案
