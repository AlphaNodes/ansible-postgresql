# Ansible Role: PostgreSQL

Installs PostgreSQL server on Debian and Ubuntu servers.

## Dependencies

  - AlphaNnodes.postgresql-client

## Example Playbook

    - hosts: db-server
      vars:
        postgresql_version: 9.5
        postgresql_with_postgis: yes
      roles:
        - AlphaNodes.postgresql

## License

GPL Version 3

## Author Information

This role was created in 2017 by [AlphaNodes](https://alphanodes.com/).
