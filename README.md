# ansible-role-mikrotik-backup

## Description

Ansible role to backup Mikrotik RouterOS configuration. It basically just take the `/export compact` value of each Mikrotik Router and then save them into a file.

## Usage

### Hosts Example

```ini
[routeros]
rou-01.ndkprd.com ansible-host=rou-01.ndkprd.com

[mikrotik:children]
routeros
```

### Playbook Example

See [Test](/tests) folder.
