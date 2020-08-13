### rabbitmq

安装:

设置用户
 rabbitmqctl add_user root root
sudo rabbitmqctl set_user_tags root  administrator
sudo rabbitmqctl set_permissions -p / root  ".*" ".*" ".*" 