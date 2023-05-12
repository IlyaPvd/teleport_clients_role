teleport_clients
=========

role for add hosts in cluster

Requirements
------------

```text
molecule_vagrant==2.0.0
molecule==5.0.0
ansible==2.14.5
```

and python 3.9+

For using role:

```text
ansible==2.14.5
```

Role Variables
--------------

```text
teleport_server: 'example.com:8080'
```

Dependencies
------------

ubuntu 20.04

Example Playbook
----------------

```text
---
- hosts: all
  roles:
   - teleport_clients
```

License
-------

BSD-3-Clause

Author Information
------------------

[IlyaPvd](https://github.com/IlyaPvd)
