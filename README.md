# Role Name

A brief description of the role goes here.

[![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-ansible--role--name-blue.svg)](https://galaxy.ansible.com/0x07cf/ansible-skeleton/)

## Requirements

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Before you [use this role](#example-playbook), some requirements must be installed:

```bash
    ansible-galaxy install -r meta/requirements.yml
```

## Role Variables

> [!WARNING]
>
> **If you want to warn the user about something regarding your variables, do so here!**

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

### Required

| Variable | Type    | Comments                              | When        |
| -------- | ------- | ------------------------------------- | ----------- |
| foo      | boolean | Set to `true` to destroy the universe | `bar: true` |

### Optional

| Variable | Default | Type    | Comments |
| -------- | ------- | ------- | -------- |
| port     | 80      | integer | 1-65535  |

## Dependencies

```yaml
- role: ceru1ean.home.role1
- role: ceru1ean.home.rol2
- role: ceru1ean.home.role3
  when: my_var
```

## Example Playbook

```yaml
- hosts: all
  vars_files:
    - vars/main.yml
  roles:
    - ceru1ean.skeleton.skeleton
```

### Example `vars/main.yml`:

```yaml
my_list:
  - abc
  - 123
```

## License

MIT

See [LICENSE](LICENSE) to see the full text.

## Author Information

This role was authored by [0x07cf](https://0x07.cf).
