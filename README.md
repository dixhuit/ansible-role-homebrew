# Ansible role: Homebrew

[![Build Status](https://travis-ci.org/danbohea/ansible-role-homebrew.svg?branch=master)](https://travis-ci.org/danbohea/ansible-role-homebrew)

- Installs Homebrew on macOS.
- Also taps additional repositories if you wish.

## Requirements

- macOS 10.13

## Role Variables

All role default variables are listed below along with their respective default values.

```yaml

# Any additional taps to add.
homebrew_taps: []

```

## Dependencies

None.

## Example Playbook

```yaml
- hosts: macbook
  connection: local

  roles:
    - role: ansible-role-homebrew
```

## License

MIT

## Author Information

This role was created by [Dan Bohea](http://bohea.co.uk) primarily for use with [Macsible](https://github.com/macsible/macsible).
