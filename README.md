Introduction
------------

This Ansible role is to set  install nginx, PHP and MySQL applications and also deploying the applications in the ubuntu 16.04 server.

Requirements
------------

ubuntu 16.04


Role Variables
--------------

While running Ansible role, you will be asked db_root_pwd, db_user, db_name and db_user_pwd as promt and you have to give this details.

Also you need to provide the following  variable details at vars/staging.yml

host:
-----
Provide the host name.

example:
--------
host: example.com

host_user:
----------
User name for the host

example:
--------

host_user: nginx

doc_root:
---------

Document root for the host

example:
--------

doc_root: /home/demo/public_html

Git_url:
--------
Github repository URL for cloning the code

example:
--------

Git_url1: https://github.com/agileblaze/PHP.git

Github repository URL for cloning database.

example:
--------

Git_url2: https://github.com/datacharmer/test_db.git

database:
---------
Database dump file

example:
--------

database: employees.sql

user_name:
----------
User name for the project

user_name: demo-project

exclude_file:


 
