Role Name
=========

Role to configure Haproxy Load Balancer

Requirements
------------
Ansible >= 2.8 and a Host Group webserver which contains all the managed host to be work as backend

Role Variables
--------------

FRONTEND_PORT: value for the port Number of the Haproxy server


Dependencies
------------

Enterprse Linux 

Example Playbook
----------------

    - hosts: servers
      roles:
      - raghav1674.balancer


Author Information
------------------

ragaws1674@gmail.com
