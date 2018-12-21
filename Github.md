# Git使用相关

## 将本地git项目上传到github

1.在项目确认为git项目
```
  git init
```
2.在github中添加Repositories，复制仓库地址

3.在本地项目中将所有文件添加到缓存,然后提交，添加远程仓库，并推送
```
  git add .
  git commit -m "first commit"
  git remote add origin github仓库地址
  git push -fu origin master
```
