Role Name
=========

A role to install the `ansible-aur` module.

https://github.com/kewlfft/ansible-aur

Requirements
------------

None.

Role Variables
--------------

You can configure the module install directory by changing the value of `library_path` in `defaults/main.yml`. 

The default install location is set to `/usr/share/ansible/plugins/modules`.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: localhost
  roles:
    - ansible_aur_install
```

License
-------

MIT.

Author Information
------------------

- [Victor Mendonça](https://victormendonca.com/) - ([GitHub](https://github.com/victorbrca))
