[![CircleCI](https://circleci.com/gh/andrewrothstein/ansible-vault-config.svg?style=svg)](https://circleci.com/gh/andrewrothstein/ansible-vault-config)
andrewrothstein.vault-config
=========

Writes a vault configuration to /etc/vault/config.hcl

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
    - andrewrothstein.vault-config
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
