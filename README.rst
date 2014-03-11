=========
Winsible
=========
Prototype for managing Windows nodes with Ansible. 

Goal
=====
#TODO

Install
=======
Master
------
#TODO: play for provisioning executor

Executor
--------

Windows
-------

Demo
=====
#TODO

Reference
=========
http://hindenes.com/trondsworking/2013/12/18/bridging-the-linux-to-windows-gap-with-ansible-and-winrm/

Future directions
=================
- refactor 'winrm' module -- it should really provide an alternative class like AnsibleWindowsModule
- refactor 'ping' role to 'win_ping' or 'ps_ping' module so managing windows feels like managing unix

