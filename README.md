# Ansible Role: ondemand_exporter

## Description

Deploy prometheus [ondemand_exporter](https://github.com/OSC/ondemand_exporter) using ansible.

## Requirements

- Ansible >= 2.9

## Role Variables

All variables which can be overridden are stored in [defaults/main.yml](defaults/main.yml)

## Example

### Playbook

Use it in a playbook as follows:
```yaml
- name: Setup ondemand_exporter
  ansible.builtin.import_role:
    name: i-mtz.ondemand_Exporter
```

## License

This project is licensed under MIT License. See [LICENSE](/LICENSE) for more details.
