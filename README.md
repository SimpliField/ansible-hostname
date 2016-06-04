Hostname
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
