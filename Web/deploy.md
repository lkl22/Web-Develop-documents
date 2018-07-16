#### Environment

node

download: [https://nodejs.org/en/download/](https://nodejs.org/en/download/)

```
tar -xvf node-v8.11.3-linux-x64.tar.xz
mv node-v8.11.3-linux-x64 /usr/local/
vim /etc/profile
    export NODE_HOME=/usr/local/node-v8.11.3-linux-x64
    export PATH=$PATH:$NODE_HOME/bin
source /etc/profile
node -v
    v8.11.3
    
//配置镜像源
npm config set registry https://registry.npm.taobao.org --global
npm config set disturl https://npm.taobao.org/dist --global
```



