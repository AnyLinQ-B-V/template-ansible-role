# Ansible Role: Template

An template for new Ansible roles.

## Requirements

None.

## Role Variables

The default values for the variables are set in `defaults/main.yml`:
```yaml
---
code here
```


**Role variables explained**

| Name | Options | Required | Description |
|---|---|---|---|
|   |   |   |   |

## Dependencies

None.

## Example Playbook

This example is taken from `molecule/default/converge.yml` and is tested on each push, pull request and release.
```yaml
---
- name: Converge
  hosts: all
  become: yes
  gather_facts: yes

  roles:
    - role: anysure.ansibletemplate
```
## License

MIT

## Author Information

This role was created in 2022 by [AnySURE](https://github.com/orgs/AnyLinQ-B-V/teams/anysure), part of [AnyLinQ B.V.](https://github.com/AnyLinQ-B-V).
