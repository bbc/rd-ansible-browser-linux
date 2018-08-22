rd-ansible-browser-linux [![Build Status](https://travis-ci.org/bbc/rd-ansible-browser-linux.svg?branch=master)](https://travis-ci.org/bbc/rd-ansible-browser-linux)
=========

This role is intended to install on top of a server based install of Ubuntu Bionic - 18 or Xenial - 16.
It installs a basic minimal GUI, web browser and some tools then allows you to specify a web browser window to load up with some configurable options such as position

Requirements
------------

This module requires Ansible 2.4

Role Variables
--------------

See defaults for variables and descriptions

Example Playbook
----------------

Example to call:

    - hosts: all
      roles:
         - { role: rd-ansible-browser-linux }
