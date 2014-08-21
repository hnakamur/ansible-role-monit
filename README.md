monit
=====

An Ansible role to install monit

Requirements
------------

None

Role Variables
--------------

- monit_daemon_timeout_seconds: 60

None

Dependencies
------------

- hnakamur.epel

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: hnakamur.monit, monit_daemon_timeout_seconds: 10 }

License
-------

MIT

Author Information
------------------

[Hiroaki Nakamura]( http://hnakamur.github.io/ )
