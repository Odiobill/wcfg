wcfg
====

Simple management of LAMP-like virtual servers for Debian and derivates

wcfg is a script, to be executed with super-user privileges, that will configure (or remove) complete LAMP-like virtual servers on Debian, Ubuntu and derivate distributions.

It supports both nginx with php-fpm and apache2 with mod_php and can manage many different things like name based virtual servers, mysql databases and privileges, (ftp) users, awstats and related static reports. logrotate will also be configured to take care of your virtual servers log files, but everything is keep consistent with the regulations and automatisms provided by the standard Debian packages.

An FTP server is not required, however a new user will be created for every virtual server, with the website root path as home directory, so it is very easy to configure per-site access installing vsftpd or any other FTP server. Moreover, always because each website belongs to a different user, you just have to install openssh to allow SFTP access.

