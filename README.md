RedHat Subscription
=========

Registers and attaches a system to a RedHat subscription.

Requirements
------------

RedHat EL subscription and system.

Role Variables
--------------

See [defaults/main.yml](redhat-subscription/defaults/main.yml) for more information.

Dependencies
------------

None.

Example Playbook
----------------

```yml
- hosts: RedHat-Systems
  roles:
    - redhat-subscription
```

License
-------

BSD
