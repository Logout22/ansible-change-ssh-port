Change SSH port
=========

Ansible role to change the host's SSH port

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
