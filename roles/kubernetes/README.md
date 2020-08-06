# Ansible Role: Kubernetes

[![Build Status](https://travis-ci.org/geerlingguy/ansible-role-php-mysql.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-php-mysql)

Installs Kubernetes (https://www.mysql.com/) support on Linux.

## Requirements

None.

## Role Variables

NONE

## Dependencies

NONE

## Example Playbook

    - hosts: meshserver
      roles:
        - { role: goldeagle.k8s }

## License

Apache-2.0

## Author Information

Bison 'goldeagle' Fan
