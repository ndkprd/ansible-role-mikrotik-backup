# Usage

## Install Requirement

```bash
ansible-galaxy install -r requirements.yaml
```

## Run Playbook

```bash
ansible-playbook -i hosts test.yaml
```

## Needed Vars

```yaml
- name: backup_dir
  type: string
  default: none
  example: "/home/{{ backup_dir_owner }}/backups/mikrotik/{{ inventory_hostname }}"
- name: backup_dir_owner
  type: string
  default: none
  example: "ansible"
```
