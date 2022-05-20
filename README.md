Mailhog Basic Auth Role
=========

An implementation of geerlingguy.mailhog adding basic auth.

Requirements
------------
- None

Role Variables
--------------

```yml
mailhog_enabled: false
mailhog_install_dir: /opt/mailhog
mailhog_version: 1.0.1
mailhog_basic_auth_enabled: false
mailhog_basic_auth_user:
mailhog_basic_auth_pass:
mailhog_basic_auth_file:
```
Dependencies
------------
- `geerlingguy.mailhog`

Example Playbook
----------------
```yaml
- hosts: servers
  roles:
    - { role: coopdevs.mailhog-basic-auth }
```
License
-------

BSD

Author Information
------------------

https://coopdevs.org