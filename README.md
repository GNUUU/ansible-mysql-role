# Ansible Role: MySQL

- Installs MySQL server on Debian/Ubuntu servers.

## Requirements

None.

## Role Variables

- Available variables are listed below, along with default values (see vars/main.yml):

mysql_root_password: root (The MySQL root user account password.)


mysql_packages:
  - mysql-server
  - python-mysqldb

Packages to be installed.  
