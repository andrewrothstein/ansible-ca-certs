[![CircleCI](https://circleci.com/gh/andrewrothstein/ansible-ca-certs.svg?style=svg)](https://circleci.com/gh/andrewrothstein/ansible-ca-certs)
andrewrothstein.ca-certs
=========

Installs the operating system default trusted CA certificates.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.ca-certs
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
