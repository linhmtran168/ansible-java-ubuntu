Role Name
=========

The role for install java 8 on ubuntu system

Role Variables
--------------
```
java_version: 8
```

Example Playbook
----------------


    - hosts: servers
      sudo: yes
      vars:
        java_version: 8
      roles:
         - linhmtran168.java

License
-------

MIT

Author Information
------------------

Linh M. Tran
