wcfg
====

Lightweight solution to manage LAMP-like virtual web servers


wcfg is a flexible and easy to customise script, to be executed with super-user privileges, that can configure (or remove) complete LAMP-like virtual web servers on Debian, Ubuntu and derivate distributions.

It supports both nginx with php-fpm and apache2 with mod_php and can manage many different things like name based virtual servers, mysql databases and privileges, (ftp) users, awstats and related static reports. logrotate will also be configured to take care of your virtual servers log files, but everything will be kept consistent with the regulations and automatisms provided by the standard Debian packages.