# 新建远程仓库

## 1.新建一个用户
```
sudo adduser git
su  git
cd ~ //切换到用户主目录
git init --bare project.git //创建一个叫project的裸仓库
```
## 2.clone到本地，上传代码
```
git clone git@服务器ip：project.git
// 如果服务器ssh端口做过修改，不是22，可使用：ssh://git@ip:端口/home/git/project.git
//添加文件后，提交到远程仓库即可
git add .
git commit -m "提交信息"
git remote add 地址名称（如origin） clone的地址
git push origin master
```
## 3.添加钩子
钩子有很多种，此处只添加post-receive，当我们提交代码到远程仓库，触发该钩子文件，我们要实现
的钩子是，当提交代码后，让服务器上的本地仓库执行更新，后续加入自动部署的代码即可
首先在服务器建立本地仓库
```
git clone 仓库地址
```
回到远程仓库文件夹，添加钩子文件
```
vim post-receive

//添加以下内容
#!/bin/sh

DEPLOY_PATH=服务器本地仓库地址
unset GIT_DIR #这条命令很重要
cd $DEPLOY_PATH
git reset --hard
git pull

//由于服务器本地仓库与远程仓库不是同一个用户，因此有权限问题，修改本地仓库文件权限
chmod -R 777 文件夹
//另外将远程仓库的账户的公钥添加到自己的authorized_keys文件中
touch .ssh/authorized_keys && chmod 600 .ssh/authorized_keys
//生成ssh-key
ssh-keygen -t rsa
sudo cat ~/.ssh/id_rsa.pub >> ~/.ssh/authorized_keys
//另外以git用户的角色，去更新下本地仓库
```


禁用shell登录
先which git-shell命令获得git-shell 的安装路径
然后 vim /etc/passwd
修改为：git:x:1001:1001:,,,:/home/git:/usr/local/bin/git-shell
