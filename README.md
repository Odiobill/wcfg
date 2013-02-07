wcfg
====

**wcfg** is an easy and lightweight solution to manage LAMP-like virtual web servers on Debian, Ubuntu and derivate distributions.

It supports both **nginx with php-fpm** and **apache2 with mod_php** and can manage many different things like name based virtual servers, **mysql** databases and privileges, **awstats** and related static reports. **logrotate** will also be configured to take care of your virtual servers log files, but everything will be kept consistent with the regulations and automatisms provided by the standard Debian packages.

An FTP server is not required, however a new user will be created for every virtual server, with the website root path as home directory. This way it is very easy to configure per-site access installing **vsftpd** or any other FTP server. Moreover, since each website belongs to a different user, you just need to install **openssh** to allow SFTP access.

