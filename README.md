# node

[![Build Status](https://travis-ci.org/m31271n/ansible-role-node.svg?branch=master)](https://travis-ci.org/m31271n/ansible-role-node)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-m31271n.node-blue.svg)](https://galaxy.ansible.com/m31271n/node)

Ansible role that setups node environment.

## Requirements

None.

## Role Variables

+ `node_major_version`: `8`

## Dependencies

None.

## Example Playbook

```
- hosts: servers
  roles:
    - role: m31271n.node
      node_major_version: 6
```

## Thanks

+ [NodeSource Node.js Binary Distributions](https://github.com/nodesource/distributions)

* * *

<p align="center">Made with ❤ by <a href="http://index.m31271n.com">m31271n</a></p>
