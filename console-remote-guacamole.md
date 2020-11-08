# Guacamole 服务端 ＋ Guacd

## 主要特性

服务基于[Apache Guacamole](https://github.com/apache/guacamole-server)，功能非常强大

* 安装较为容易，支持docker, 需要初始化Mysql或者PostgreSql数据库

* 支持多帐号，多group，多profile

* 安全性高，支持屏幕录制，访问记录

* 功能强大, 支持只读模式和profile分享，支持文件传输

* 支持多种认证方式,可使用[HTTP请求头认证](http://guacamole.apache.org/doc/gug/header-auth.html)与Edgora控制台服务代理集成

## 安装

请参照[官方文档](http://guacamole.apache.org/doc/gug/guacamole-docker.html)或者[第三方安装文档](https://github.com/MysticRyuujin/guac-install)