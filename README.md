# ANSIBLE-TMUX-CONFIG

Custom configuration of tmux

## Role Variables

Stored in defaults folder

```
```

## Howto use this role

This role needs to be included in a playbook
You can install it with *Galaxy*

```bash
ansible-galaxy install -r requirements.yml
```

requirements.yml
```
- src: probakilla.tmux_config
```

# Requirements

- Ansible 2.4+

# Example playbook using this role

You can include this role in an ansible playbook file like this:

```
- hosts: all
  roles:
    - role: probakilla.tmux_config
      tags: mytags
```
