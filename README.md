# unbound

[![Build Status](https://travis-ci.com/1mr/ansible-role-unbound.svg?branch=master)](https://travis-ci.com/1mr/ansible-role-unbound)

This role helps to install and configure unbound.

## Requirements

This role requires ansible 2.5 or higher.

## Role Variables

## Dependencies

None

## Example Playbook

    - hosts: servers
      roles:
         - { role: 1mr.unbound, tags: unbound }

## License

MIT

## Author Information

This role was created by Stas Stavnichuk.
