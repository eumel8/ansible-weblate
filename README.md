Ansible Weblate Deployment
==========================

Weblate is a web based translation platfrm written in Python/Django.
Here are some Ansible playbooks to install and configure Weblate.

Prerequisites:
--------------

  - Ubuntu 18.04 (bionic)
  - Python 3xx
  - Ansible >2.6

wl-install.yml  
--------------

Main installer. Installs Weblate with latest pip version in venv

wl-mysql.yml  
------------

Helper to install and configure MySQL

wl-apache.yml  
-------------

Helper to install and configure Apache with WSGI

wl-projects.yml
---------------

Create projects and components from OpenStack Community
