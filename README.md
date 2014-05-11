avanov.circus
==============================

Ansible role for [Circus](https://circus.readthedocs.org/en/latest/)

Install it with the following command:

```bash
$ ansible-galaxy install avanov.circus
```

Requirements
------------

At least one version of ``pip`` must be present in a target system. You can use either
system-wide or virtualenv-specific version of pip by providing a path to the ``circus_pip_path``
variable described below.

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