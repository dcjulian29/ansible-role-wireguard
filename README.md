# Ansible Role: wireguard

[![Lint](https://github.com/dcjulian29/ansible-role-wireguard/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-wireguard/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-wireguard.svg)](https://github.com/dcjulian29/ansible-role-wireguard/issues)

This an Ansible role to install and configure WireGuard VPN.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.wireguard
  src: https://github.com/dcjulian29/ansible-role-wireguard.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
