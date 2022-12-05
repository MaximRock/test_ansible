Role Name
=========

Installation php-fpm and configuration nginx

Role Variables
--------------

 package name
name_package: php8.1-fpm

- content file php info
content: "<?php 
              echo phpinfo();
          ?>"
ath to file
path: "/opt/nginx/ansible"

- file name index.php
file_name: "index.php"