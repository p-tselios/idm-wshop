# rhidm_manage_sudo

This role manages SUDO rules in an IdM domain.

### SUDO rules 

SUDO rules are defined in one list: 

* rhidm_sudo_rules

### SUDO commands and command groups
SUDO commands and command groups are defined in one list: 

* rhidm_sudo_cmd_groups

## Requirements

* A running Red Hat IDM / FreeIPA server
* [FreeIPA Ansible collection](https://github.com/freeipa/ansible-freeipa) installed
* Ansible 2.9+

## Dependencies

None

## Example Playbook

```yaml
---
- name: Create RH IDM content
  hosts: rhidms_master
  roles:
    - rhidm_manage_sudo
```

## License
GPLv3

## Author Information 
Peter Tselios (ptselios@redhat.com)
