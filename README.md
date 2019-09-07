# Ansible Role: Docker Available

[![Build Status](https://travis-ci.org/aem-design/ansible-role-docker-available.svg?branch=master)](https://travis-ci.org/aem-design/ansible-role-docker-available)

This role tests if Docker is available on host
> This role was developed as part of
> [AEM.Design](http://aem.design/)

## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

```yaml
- hosts: all
  roles:
    - { 
      role: aem_design.docker_available
    }
```

## License

Apache 2.0

## Author Information

This role was created by [Max Barrass](https://aem.design/).