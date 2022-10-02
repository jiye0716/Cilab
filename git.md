# Git
* 版本控制系統
* 共同開發

git repo：存放project的地方

## git config --global user.name "xxxxx"

## git config --global user.email xxxxxxx@example.com

## git init
    (initial)
    初始化repo

## git pull 
    從遠端repo拉取回本地（同步）

## git clone
    從遠端repo複製資料

## git status
    顯示修改檔案清單
    -s：僅會顯示已修改的檔案名稱

## git add .
    git add <檔案名稱>
    將子目錄裡的所有檔案註冊到索引裡

## git commit
    -a : 有修改的檔案(不包括新增的檔案)，將其加入索引並提交。
    -m : 提交訊息

## git push
    從本地推送到遠端
    git push origin master 本地master分支推一份到origin節點
    git push -u origin master 把預設remote都設成origin

## git reset -- <file name>
    把add的檔案unstage回去

## git checkout -- <file>
    把檔案回到上次commit的狀態

## git reset --soft HEAD~1
    往前退一個commit(保留修改的部分）
    
## git rm
    remove

## git remote add <自訂名稱> <網址>
    把這個網址加到你的remote 
    git remote add origin xxx.github

## git remote
    查看所有remote
---
# 設定ssh連線

## ssh -keygen
    產生公鑰與私鑰

## cd /c/Users/

## ls -al
    顯示目錄下物件

## cat id_rsa.pub
    顯示內容
