## 1.配置用户名和邮箱
***
```git
  git config user.name "姓名"
  git config user.email "邮箱地址"
```
***
## 2.创建一个新仓库
```git
git clone 仓库地址
cd web
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master
```
***
## 3.推送现有文件夹
```git
cd existing_folder
git init
git remote add origin 仓库地址
git add .
git commit -m "Initial commit"
git push -u origin master
```
***
## 4.推送现有的git仓库
```git
cd existing_repo
git remote rename origin old-origin
git remote add origin 仓库地址
git push -u origin --all
git push -u origin --tags
```
***
## 5.添加新库并命名为upstream
```git
git remote add upstream 仓库地址
```
***
## 6.查看已关联的远程仓库
```git
git remote -v 
```
***
## 7.删除名为upstream的库
```git
git remote rm upstream
```