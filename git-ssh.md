# git的下载和安装及ssh获取

## 一、git的下载与安装

### 1.git下载

下载方式：通过官网下载 https://git-scm.com/download/win

## ![1](C:\Users\fh060909\Desktop\1.png)

### 2.git安装

按照默认选项点击next，最后install



### 3.使用

在桌面右键，点击open git bash here,输入 

ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

连续点击三次回车，即可生成ssh密钥及公钥

![2](C:\Users\fh060909\Desktop\2.png)

用记事本软件打开公钥，将文本复制到GitHub创建ssh的地址，即可使用。