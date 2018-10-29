uniQconsulting.nextcloud
=================

* install nextcloud on centos 7
* install dependencies: nginx, php, redis, mariadb
* generate ssl cert (self signed) if nextcloud_use_https is true

Requirements
------------

* Currently only tested with CentOS 7

Role Variables
--------------
Variables are self speaking or documented in:   
* `defaults/main.yml`
* `vars/main.yml`


example playbooks for this role are located in `test` folder:
--------------
* `tests/install_nextcloud_and_collabora.yml`
* `tests/install_nextcloud_https.yml`
* `tests/install_nextcloud_http.yml`

License
--------------
https://opensource.org/licenses/LGPL-3.0    
Copyright (c) uniQconsulting ag - Chris Ruettimann <cruettimann@uniqconsulting.ch>

