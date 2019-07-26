stackroute.vlab-remote-common
=========

VLAB RDP Setup for StackRoute.

It installs and configures the following:

- xrdp
- mate

Requirements
------------

Must have applied `stackroute.spring-boot-fsd` role first.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

```
- hosts: servers
  roles:
    - role: stackroute.vlab-remote-common
```

License
-------

MIT

Author Information
------------------

- [Sagar Patke](https://github.com/sagarpatkeatl), [StackRoute] (http://stackroute.in)
