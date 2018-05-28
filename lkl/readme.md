wget --no-check-certificate https://github.com/91yun/uml/raw/master/lkl/install.sh && bash install.sh

判断
ping 10.0.0.2




如果修改转发端口
修改 /root/lkl/run.sh ，查找 9000-9999 ，改成你想要的端口段
修改 /root/lkl/haproxy.cfg 查找 9000-9999 ，改成你想要的端口段
重启 vps