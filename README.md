# Minernat Windows代理工具箱

# 一、	简介
### 为hellominer websocket本地加密协议提供的加密代理工具。
### 一个运行在VirtualBox中的Debian内核。高效、轻量，易管理、开箱即用、有web管理后台。
# 二、	下载使用
### 1.	下载`windows-minernat.7z`并解压，得到`tools`文件夹。 ![1.1](/pic/1.png) [点击下载](https://github.com/hellominer/tools/releases/download/windows-minernat/windows-minernat.7z)
### 2.	进入`tools`文件夹并安装`VirtualBox-6.1.32-149290-Win.exe`（均默认即可）
### 3.	双击打开`加密代理.ova`  ![1.2](/pic/2.png)
### 4.	选择导入点击`向导模式`
![1.3](/pic/3.png) 
### 5.	选择 `加密代理.ova` 文件所在位置 并导入
### 6.	重要步骤！！ 选择设置-->网络  将连接方式选择为桥接网卡  界面名称选择自己的有线网卡。（图中为我电脑的有线网卡，请根据自己情况选择）
![1.4](/pic/4.png)  
### 7.	启动虚拟机，用户名为:`root` 密码:`123456`。
### 8.	输入指令 `ifconfig enp0s3`获取虚拟机ip
### 9.	访问虚拟机ip进入虚拟机管理后台可以修改代理参数

# 问题交流

### 如果您遇到使用问题，欢迎加入telegram交流群 [点击加入](https://t.me/hellominer_group) 寻求帮助。
