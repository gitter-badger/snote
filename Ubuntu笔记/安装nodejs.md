#### 安装
```bash
wget http://mirrors.ustc.edu.cn/node/v8.11.1/node-v8.11.1-linux-x64.tar.xz
# 手动解压
sudo cp -frp node-v8.11.1-linux-x64/* /usr/local
```
#### 换源
```bash
npm config set registry https://registry.npm.taobao.org/
npm config set registry https://registry.npmjs.org/

npm config get registry
```
