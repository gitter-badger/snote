## 开启sudo
```bash
visudo
username ALL=(ALL) ALL  
```
## 安装无线网卡Broadcom Corporation BCM43142 802.11b/g/n
```bash
wget http://mirrors.163.com/debian/pool/non-free/b/broadcom-sta/broadcom-sta-dkms_6.30.223.271-8~bpo8+1_all.deb
```
## virtualbox 的usb识别问题
```
安装 插件包
sudo adduser 用户名 vboxusers
重启
id查看是否有usb
```
