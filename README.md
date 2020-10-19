### 1.09更新说明

更新部分组件，兼容centos8，支持centos7/8。

该版本不再支持centos6，可以使用1.06版本安装在centos6系统。

更多配置和详细信息请参考文档

### EwoMail

EwoMail是基于Linux的开源邮件服务器软件，集成了众多优秀稳定的组件，是一个快速部署、简单高效、多语言、安全稳定的邮件解决方案，帮助你提升运维效率，降低 IT 成本，兼容主流的邮件客户端，同时支持电脑和手机邮件客户端。

### 集成组件


Postfix：邮件服务器SMTP

Dovecot：IMAP/POP3/邮件存储

Amavisd：反垃圾和反病毒

LNAMP：，nginx，mysql，php

EwoMail-Admin：WEB邮箱管理后台

Rainloop：webmail

### 安装环境

centos6/7系统，服务器需要干净环境，全新安装的系统。

最低配置要求

CPU：1核

内存：1G

硬盘：40G

### 检查swap

安装前需要swap缓存，请务必先检查swap是否已经启动。

### 手动安装

下载并重新命名为ewomail.zip


```
解压安装
unzip -o ewomail.zip
cd EwoMail/install
#需要输入一个邮箱域名，不需要前缀，列如下面的ewomail.cn
sh ./start.sh ewomail.cn
```

 **国外网络** 请在安装域名后面加空格加en，例如  sh ./start.sh ewomail.cn en

### 文档教程

安装和文档教程

http://doc.ewomail.com/docs/ewomail/install



### 邮箱后台

![ewomail-admin](https://images.gitee.com/uploads/images/2019/1231/142334_74d987df_325053.png "ewomail-admin")

### webmail

![webmail](https://images.gitee.com/uploads/images/2019/1231/142334_6daf7a2a_325053.png "webmail")

### 安装或使用过程遇到问题

http://doc.ewomail.com/docs/ewomail/solve
