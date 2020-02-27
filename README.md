# Ansible Role: PostgreSQL

Installs PostgreSQL server on Debian and Ubuntu servers.

[![Build Status](https://travis-ci.org/AlphaNodes/ansible-postgresql.svg?branch=master)](https://travis-ci.org/AlphaNodes/ansible-postgresql)


## Dependencies

  - AlphaNnodes.postgresql-client

## Example Playbook

    - hosts: db-server
      vars:
        postgresql_version: '11'
        postgresql_with_postgis: yes
      roles:
        - AlphaNodes.postgresql

## License

GPL Version 3

## Author Information

This role was created in 2018 by [AlphaNodes](https://alphanodes.com/).
