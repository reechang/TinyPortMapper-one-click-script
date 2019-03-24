# tinyPortMapper
tinyPortMapper 一键安装脚本

# 和screen一起使用更佳
```
apt-get install screen

screen -S tinyport

```

# 常规使用方法
```
tinymapper  -l <listen_ip>:<listen_port> -r <remote_ip>:<remote_port>  [options]
```
# 也可以作为 6to4 或 4to6 使用
```
tinymapper -l0.0.0.0:1234 -r[2001:19f0:7001:1111:00:ff:11:22]:443 -t -u
tinymapper -l[::]:1234 -r44.55.66.77:443 -t -u
```
