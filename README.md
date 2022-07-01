# Ansible Role: Anki
[![CI](https://github.com/skaary/ansible-role-anki/actions/workflows/ci.yml/badge.svg?branch=main&event=push)](https://github.com/skaary/ansible-role-anki/actions?query=workflow%3Ci)

An Ansible Role that installs [Anki](https://apps.ankiweb.net/) on Linux.

## Requirements

None

## Dependencies

None

<!-- ## Example Playbook -->
## Installation

Download the role directly from git by typing into your terminal:

```bash
ansible-galaxy install git+https://github.com:skaary/ansible-role-anki.git
```
 <!-- ansible-galaxy install -p ./roles git+https://github.com:skaary/ansible-role-anki.git -->
or

```bash
ansible-galaxy install git+https://github.com:skaary/ansible-role-anki.git,,anki
```

to change the installed role name from _ansible_role_anki_ to just _anki_.

Alternatively, install the role via a _requirements.yml_ file, e.g. when installing multiple roles at once. See https://galaxy.ansible.com/docs/using/installing.html#installing-multiple-roles-from-a-file for more information.

## Example playbook

```yaml
- hosts: all
  roles:
    # - skaary.anki
    - ansible-role-anki
```

## License

MIT / BSD