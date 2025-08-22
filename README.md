# postgresql_container_setup

=========

Ansible role to deploy official PostgreSQL docker containers

## Requirements

## Role Variables

## Dependencies

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

## Example Playbook

```yaml
---
- name: PostgreSQL setup
  hosts: all
  gather_facts: true

  roles:
    - postgresql_container_setup
...
```
