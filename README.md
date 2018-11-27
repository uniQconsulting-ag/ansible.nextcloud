[![Build Status](https://travis-ci.org/uniQconsulting-ag/ansible.os-basic.svg?branch=master)](https://travis-ci.org/uniQconsulting-ag/ansible.nextcloud)

[![Alt text](https://www.uniqconsulting.ch/images/logo.png)](https://www.uniqconsulting.ch/)

Nextcloud Setup with Ansible
=================

* install nextcloud on centos 7
* install dependencies: nginx, php, redis, mariadb
* generate ssl cert (self signed) if nextcloud_use_https is true

Requirements
------------

* Currently only tested with CentOS 7
* Ansible 2.4 or higher is required for this Ansible Role

Role Variables
--------------
Variables are self speaking or documented in:   
* `defaults/main.yml`
* `vars/main.yml`

Dependencies
------------

* `uniqconsulting.mariadb`
* `uniqconsulting.collabora`

Example Playbook
----------------

Example playbooks for this role are located in ´test´ folder:
* `tests/install_nextcloud_and_collabora.yml`
* `tests/install_nextcloud_https.yml`
* `tests/install_nextcloud_http.yml`

uniQconsulting ag
-----------------

uniQconsulting ag is a company in Switzerland with Offices in Bassersdorf, Basel and St. Gallen

License
--------------
https://opensource.org/licenses/LGPL-3.0    
Copyright (c) uniQconsulting ag - Chris Ruettimann <cruettimann@uniqconsulting.ch>

