# 服务器

### Yum安装

1、安装erlang

```
wget http://dl.fedoraproject.org/pub/epel/6/x86_64/epel-release-6-8.noarch.rpm
sudo rpm -Uvh epel-release-6-8.noarch.rpm
sudo yum install erlang
```

2、安装RabbitMQ

```
sudo rpm --import http://www.rabbitmq.com/rabbitmq-signing-key-public.asc
wget http://www.rabbitmq.com/releases/rabbitmq-server/v3.3.3/rabbitmq-server-3.3.3-1.noarch.rpm
sudo yum install rabbitmq-server-3.3.3-1.noarch.rpm
```
