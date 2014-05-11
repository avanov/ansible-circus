avanov.circus
==============================

Ansible role of Circus

Install it with the following command:

```bash
$ ansible-galaxy install avanov.circus
```

Requirements
------------

None

Role Variables
--------------

Here is the list of all variables and their default values:

* ``circus_tmp_remote_path: /tmp`` - used for uploading pip requirements file
* ``circus_pip_path: /usr/bin/pip`` - used for installing python packages


Dependencies
------------

None

Example Playbook
-------------------------

    - hosts: servers
      roles:
         - {role: avanov.circus }

License
-------

MIT

Author Information
------------------

Maxim Avanov (https://maximavanov.com)