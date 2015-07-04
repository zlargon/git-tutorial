# Git

這份教學適用於任何想自學 Git，或是想要更了解 Git 的人

教學內容會由淺入深，逐步把 Git 的概念全部帶出來

內容三大部分：

1. 本機篇
    * 基本操作
    * 新增/修改/刪除 patch
    * 操作 branch
2. 遠端篇
3. 進階篇

講解時，全都是在終端機 `command line` 的方式進行操作

* 使用 Windows 的人建議安裝 Git 官方所提供的 `Git Bash`

<br>

## 為何要學 Command Line

可能很多人都已經很習慣使用視覺操作介面 (GUI) 的軟體，但為何要學 Command Line 操作呢？

Git 原本就被是設計成 command line，因此用它可以更貼近原作者 (Linus Torvalds) 的設計概念

任何第三方所開發的 Git 視覺操作介面，其實最終都是透過 command line 去呼叫 git 的指令

雖然視覺操作介面很方便，但是每個軟體的操作都不盡相同（尤其是一些比較複雜的 git 指令）

搞懂這些 git 指令後，不論要轉換使用哪個 GUI 都會非常容易上手，而切換 GUI 時也不用從頭再學一次

若未來要在 server 上透過 git 來部署應用程式，也只能用 command line 來操作呀~

為了要學習會最原汁原味的 Git，最有投資報酬率的方式，學習 command line 會是最佳的方式！

<br>

## Git 常用指令

這裡只會教以下常用的 27 個指令，然後我自行對他們的性質進行分類

#### 初始化、設定 (2)
* init
* config

#### 查看狀態 (4)
* status
* log
* show
* diff

#### 新增/修改 patch (4)
* add
* rm
* mv
* commit

#### 刪除 patch (3)
* reset
* revert
* reflog

#### branch 相關指令 (3)
* branch
* checkout
* cherry-pick

#### 合併 branch (2)
* merge
* rebase

#### 遠端協同指令 (5)
* clone
* remote
* fetch
* pull
* push

#### 進階指令 (4)
* stash
* submodule
* tag
* svn
