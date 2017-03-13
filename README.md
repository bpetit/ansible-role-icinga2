Icinga2
=======

This role provides Icinga2 monitoring instance installation and configuration.

Requirements
------------

Ansible: 2.0.1

Log as root on the remote host (ansible-playbook -u root)

Tested on:

- Debian Jessie 8.1

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

      - hosts: monitoring
        roles:
          - role: icinga2

License
-------

BSD

Todo
----

- Fill configuration files to avoid needing the setup wizard.
