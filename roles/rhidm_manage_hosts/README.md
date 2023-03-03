# rhidm_manage_hosts

This role manages hosts, hostgroups and hostgroups automember rules in an IdM domain.

### Host Groups

Host groups are defined in one list: 

* rhidm_host_groups_list

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
