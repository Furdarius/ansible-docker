# Ansible Role: Docker
[![Build Status](https://travis-ci.org/Furdarius/ansible-docker.svg?branch=master)](https://travis-ci.org/Furdarius/ansible-docker)

Install [Docker Engine](https://docs.docker.com/engine/userguide/intro/) on
remote machine.

## Variables

All variables can be found in [defaults/main.yml](https://github.com/Furdarius/ansible-docker/blob/master/defaults/main.yml)

## Playbook example

```yaml
---
- hosts: all
  become: true
  roles:
    - docker
```
