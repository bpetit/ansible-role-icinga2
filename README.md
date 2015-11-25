Icinga2
=======

This role provides Icinga2 monitoring instance installation and configuration.

Requirements
------------

Ansible: 1.9.3

Log as root on the remote host (ansible-playbook -u root)

Role Variables
--------------

    icinga2_vim_config_path
    icinga2_db_user_passwd
    icinga2_db_user_name
    icinga2_db_name
    icinga2_db_postgresql_version
    icinga2_db_postgresql_pg_hba_conf_path
    icinga2_timezone

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

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
