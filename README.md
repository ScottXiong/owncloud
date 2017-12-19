# owncloud error : You are accessing the server from an untrusted domain
http://blog.csdn.net/smhbqc/article/details/53258270

# 修改config/config.php配置
```
cd /data/www/default/owncloud/config/
vi config.php
put the ip you trust in the Array.
/etc/init.d/httpd restart
```
