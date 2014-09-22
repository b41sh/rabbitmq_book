# 配置

RabbitMQ的默认配置可以满足大多数的运行情况，如果有特殊需求，可以通过如下三种方式来配置：

* 环境变量(environment variables)
* 配置文件(a configuration file)
* 运行时参数和策略(runtime parameters and policies)

环境变量由rabbitmq-env.conf文件定义，配置文件由rabbitmq.config文件定义。这些文件的路径在不同发行版是不同的，例如：

* Generic UNIX - $RABBITMQ_HOME/etc/rabbitmq/
* Debian - /etc/rabbitmq/
* RPM - /etc/rabbitmq/
* Mac OS X (Macports) - ${install_prefix}/etc/rabbitmq/,the Macports prefix is usually /opt/local
* Windows - %APPDATA%\RabbitMQ\

如果rabbitmq-env.conf文件不存在，只能在默认路径手动创建。

如果rabbitmq.config文件不存在，可以在手动创建文件，路径由环境变量RABBITMQ_CONFIG_FILE指定。

文件修改之后需要重启服务器。
