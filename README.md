# Ansible role: Homebrew

[![Build Status](https://travis-ci.org/danbohea/ansible-role-homebrew.svg?branch=master)](https://travis-ci.org/danbohea/ansible-role-homebrew)

Installs Homebrew & Homebrew Cask on Mac OS X.

## Requirements

- Mac OS 10.9+


## Role Variables

None.


## Dependencies

None.


## Example Playbook

```
- hosts: macbook
  connection: local

  roles:
    - role: ansible-role-homebrew
```

## License

MIT


## Author Information

This role was created by [Dan Bohea](http://bohea.co.uk) primarily for use with [Macsible](https://github.com/danbohea/macsible).
