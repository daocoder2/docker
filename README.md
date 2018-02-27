小白初步尝试 contos7 下 利用docker搭建lnmp环境。

php7.1 + nginx1.13 + mysql5.7 + redis:3.2 + memcached:1.5 

欢迎交流学习，不断更新中。

默认配置开启80和2334两个端口。

80端口用于www下监听项目地址，需要在nginx.conf中自行配置。

2334端口直接监听www地址，用于检测各容器通信及工作是否正常。