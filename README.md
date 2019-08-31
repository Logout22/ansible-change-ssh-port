Change SSH port
===============

Ansible role to change the host's SSH port, which is useful against brute force attacks.

Inspired by https://dmsimard.com/2016/03/15/changing-the-ssh-port-with-ansible/

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

    ---
    - name: Set up SSH port
      hosts: site
      gather_facts: no
      roles:
      - change-ssh-port

License
-------

GPLv3
