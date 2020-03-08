# jonsible.yay

[![Build Status](https://travis-ci.com/jonsible/yay.svg?branch=master)](https://travis-ci.com/jonsible/yay)
[![Galaxy](https://img.shields.io/badge/galaxy-jonsible.yay-blue.svg)](https://galaxy.ansible.com/jonsible/yay/)

Role to install yay

## Requirements

None.

## Role Variables

### Default usage

As default yay is installed and running.
If you want to adapt this to your needs look at the [Advanced usage](#advanced-usage) section.

### Advanced usage

For more advanced usage the following variables are available:
```yaml
aur_user: aur_builder
```

## Dependencies

None

## Example Playbook

Install yay with the default settings
```yaml
- hosts: all
  roles:
     - role: jonsible.yay
```

## License

GPL-3.0-or-later

## Author Information

This role was created in 2020 by [Jonathan Scherrer].
