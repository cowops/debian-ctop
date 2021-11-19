Debian-ctop
============

concise commandline monitoring for containers

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cowops.debian_ctop }

Tasks
-----

  - Install [ctop](https://ctop.sh/) command line tool


License
-------

BSD
