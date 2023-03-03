# rhidm_manage_groups

This role manages user groups and user group automember rules in an IdM domain.

### Groups

Groups are defined in one list: 

* rhidm_group_list

### Automember rules
Automember rules have their own list but it is generated on the fly during the execution of the role. 

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
    - rhidm_manage_groups
```

## License
GPLv3

## Author Information 
Peter Tselios (ptselios@redhat.com)
