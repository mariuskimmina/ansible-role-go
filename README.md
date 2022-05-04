# Ansible Role: Go

Install Go, the programming language, on any Linux distrobution.

## Dependencies

None

## Example playbook

```
---
- hosts: localhost
  roles:
    - { role: mariuskimmina.go }
  become: true
```

## Tests

Fully tested on:

* Fedora 36
* Ubuntu 20.04
