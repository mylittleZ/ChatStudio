# chatStudio
## 效果图
![](https://github.com/mylittleZ/ChatStudio/blob/master/src/image/22.jpg) 

(拿qq截的图有点糊)


## 后台监听状态
打印离开or上线人数，同时在聊天界面中也会系统提示上线or离开用户

![](https://github.com/mylittleZ/ChatStudio/blob/master/src/image/111.png) 

## 运行方式
```bash

# 安装项目依赖

yarn 或者 npm install

# 运行以下命令打开浏览器的localhost:3000查看

cd chatStudio
node server.js
```
## 技术栈
> jquery+express+socket.io

## 实现功能
（1）基于Express搭建聊天室后台，作为静态服务器

（2）通过socket.io模块实现WebSocket通信

（3）通过FileReader实现发送聊天图片的读取和展示

（4）支持发送表情，自定义消息字体颜色，系统提示在线人员状态（进入/离开）

