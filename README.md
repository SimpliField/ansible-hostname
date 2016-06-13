Hostname [![Build Status](https://travis-ci.org/SimpliField/ansible-hostname.svg?branch=master)](https://travis-ci.org/SimpliField/ansible-hostname) [![Ansible Role](https://img.shields.io/ansible/role/10149.svg?maxAge=2592000)](https://galaxy.ansible.com/SimpliField/hostname/)
=========

Setup machine hostname

Requirements
------------

Need ansible 2+

Role Variables
--------------

```yaml
# By default
hostname: "{{ inventory_hostname }}"
```

Dependencies
------------

There is no dependency.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - { role: SimpliField.hostname, hostname: "MyAwesomeServer" }
```

License
-------

BSD
