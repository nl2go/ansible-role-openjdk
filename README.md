[![Build Status](https://travis-ci.org/nl2go/ansible-role-openjdk.svg?branch=master)](https://travis-ci.org/nl2go/ansible-role-openjdk)
[![Ansible Galaxy](https://img.shields.io/badge/role-nl2go.openjdk-blue.svg)](https://galaxy.ansible.com/nl2go/openjdk/)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/nl2go/ansible-role-openjdk)](https://galaxy.ansible.com/nl2go/openjdk)
[![Ansible Galaxy Downloads](https://img.shields.io/ansible/role/d/48976.svg?color=blue)](https://galaxy.ansible.com/nl2go/openjdk/)

# Ansible Role: OpenJDK

An Ansible Role that manages installation and configuration of [OpenJDK](https://openjdk.openjdk.net/).

## Role Variables

Available variables listed below, along with default values (see `defaults/main.yml`):

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - nl2go.openjdk

## Development

Use [docker-molecule](https://github.com/nl2go/docker-molecule) following the instructions to run [Molecule](https://molecule.readthedocs.io/en/stable/)
or install [Molecule](https://molecule.readthedocs.io/en/stable/) locally (not recommended, version conflicts might appear).

Provide Hetzner Cloud token:

    export HCLOUD_TOKEN=123abc456efg

Use following to run tests:

    molecule test --all

## Maintainers

- [build-failure](https://github.com/build-failure)

## License

See the [LICENSE.md](LICENSE.md) file for details.

## Author Information

This role was created in 2020 by [Newsletter2Go GmbH](https://www.newsletter2go.com/).
