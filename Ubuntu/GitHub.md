#### 设置git
```bash
git config --global user.name "jacksao"
git config --global user.email "jacksao@aliyun.com"
```
#### 创建新仓库
```bash
echo "# demo" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/jacksao/demo.git
git push -u origin master
```

#### 导入新仓库
```bash
git remote add origin https://github.com/jacksao/demo.git
git push -u origin master
```

#### 创建ssh密钥
```bash
ssh-keygen -t rsa -b 4096 -C "jacksao@aliyun.com"
sudo apt-get install xclip
xclip -sel clip < ~/.ssh/id_rsa.pub
# 测试
ssh -T git@github.com
```
