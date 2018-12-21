# gitbook安装
## nodejs安装

### 1.windows
直接上官网下载
```
  https://nodejs.org/en/download/
```
### 2.linux
下载二进制包，解压即可
![](assets/markdown-img-paste-20181018170533261.png)
```
  tar zxvf node-v0.10.26-linux-x64.tar.gz
  ln -s /home/kun/mysofltware/node-v0.10.26-linux-x64/bin/node /usr/local/bin/node
  ln -s /home/kun/mysofltware/node-v0.10.26-linux-x64/bin/npm /usr/local/bin/npm
  node -v
  npm -v
```
## gitbook安装
### 1.gitbook-cli安装

```
  npm install gitbook-cli -g
```
### 2.gitbook安装

新建一个文件夹，执行初始化即可
```
  gitbook init
```
需耐心等待，下载较慢，且前半段没过程提示
