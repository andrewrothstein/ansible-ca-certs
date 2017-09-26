andrewrothstein.ca-certs
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-ca-certs.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-ca-certs)

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
