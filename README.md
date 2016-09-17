# Ansible Role: PostgreSQL

Installs PostgreSQL server on Debian and Ubuntu servers.

## Dependencies

  - AlphaNnodes.postgresql-client

## Example Playbook

    - hosts: db-server
      vars:
        jenkins_hostname: jenkins.example.com
      roles:
        - geerlingguy.jenkins

## License

MIT (Expat) / BSD

## Author Information

This role was created in 2014 by [Jeff Geerling](http://www.jeffgeerling.com/), author of [Ansible for DevOps](https://www.ansiblefordevops.com/).
