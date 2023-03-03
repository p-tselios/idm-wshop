# rhidm_manage_hbac

This role manages HBAC rules in an IdM domain.

### Host Groups

HBAC rules are defined in one list: 

* rhidm_hbac_rules

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
    - rhidm_manage_hbac
```

## License
GPLv3

## Author Information 
Peter Tselios (ptselios@redhat.com)
