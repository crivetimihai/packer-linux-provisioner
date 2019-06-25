Role Name
=========

Packer: Linux provisioner base. Basic framework for packer provisioning tasks.

Requirements
------------

Tested on: RHEL 8 / CentOS 7 / Fedora 30.

Role Variables
--------------

N/A.

Dependencies
------------

N/A.

Example Playbook
----------------

```
---
- hosts: all
  become: yes
  gather_facts: yes

  roles:
    - crivetimihai.packer-linux-provisioner
```

License
-------

BSD


Author Information
------------------

Mihai Criveti.
