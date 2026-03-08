# git指令集

### Markdown
https://hackmd.io/@howkii-studio/markdown_intro

### 檢視版本號
- git version

### 註冊全域資訊
- git config --global user.name cathy

- git config --global user.email cathy@gmail.com

### 初始化倉庫
- git init
- .git/

### 控管狀態
- U -> Untrack (為未追蹤)
- A -> Added (已加入)
- D -> Deleted(已刪除)
- M -> Modified(已變更)

### 加入控管
- git add 1.txt
- git add . (加入所有變動，包含所有變動)

### 檢視狀態
- git status

### 恢復
- git restore 1.txt

### 加入不控管的項目
- .gitignore

### 檢視暫存區狀態
- git ls-files -s

### 恢復上一動
- git checkout filename
- git checkout . (恢復全部檔案)

### 加入倉庫
- git commit -m "專案初始化完成1150308"
- git commit --amend (跟最新的commit合併)


### 檢視倉庫
- git log
- git log --oneline

### 分支的概念
- master(主分支)
- git branch

### 切換commit
- git checkout commit-sha前5碼
	-觀察當時的程式碼
- git checkout master

### 新增分支
- git branch test

### 切換分支
- git checkout test

### 合併分支
- master合併test分支，先切回master分支，再merge test分支
- git checkout master 
- git merge test

### 申請github

### 綁定到雲端
- git remote add origin https://github.com/tunging1234/git-demo.git

### 檢視雲端網址
- git remote -v

### 推送到雲端
- git push
- git push -u origin master (第一次)
- git push -f
	- force 強制推

### 從雲端拉取
- git pull

### 複製專案
- git clone https://github.com/tunging1234/git-demo.git

### 

### VSCODE
- ctrl+shift+p 進階搜尋
- 更改終端機
	- default terminal ==> cmd.exe


 