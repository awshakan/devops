#!/bin/bash

sudo su

yum update -y

yum install -y httpd php mysql  php-mysql git

systemctl start httpd

chkconfig httpd on

echo 'test123' > /var/www/html/index.html
