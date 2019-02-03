[![Build Status](https://travis-ci.org/marvel-nccr/ansible-role-ansible-prerequisites.svg?branch=master)](https://travis-ci.org/marvel-nccr/ansible-role-ansible-prerequisites)

# Ansible Role: marvel-nccr.ansible_prerequisites

Install prerequisites for running ansible on Ubuntu.

## Installation

`ansible-galaxy install marvel-nccr.ansible_prerequisites`

## Role Variables

See `defaults/main.yml`

## Example Playbook

Note: Set `gather_facts: no` when running this role.

```
  - hosts: servers
    gather_facts: no
    roles:
    - role: marvel-nccr.ansible_prerequisites
```

## License

MIT

## Contact

Please direct inquiries regarding Quantum Mobile and associated ansible roles to the [AiiDA mailinglist](http://www.aiida.net/mailing-list/).
