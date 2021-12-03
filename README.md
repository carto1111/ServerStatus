# ServerStatus

复制themes的下任意主题到程序的目录下，改名theme 即可启用主题，可以进行自行编辑html,js,css,images

`wget https://github.com/bianzhifu/ServerStatus/releases/download/v1.0.0/ServerStatus_linux_amd64 && chmod a+x ServerStatus_linux_amd64 && ./ServerStatus_linux_amd64 -port=8888 -theme=badafans &`

Liunx启动项    
修改里面的ServerStatus.service路径端口等信息    
然后放到/etc/systemd/system/目录下运行下面三个命令    
systemctl daemon-reload     
systemctl enable ServerStatus.service    
systemctl restart ServerStatus.service    
  
