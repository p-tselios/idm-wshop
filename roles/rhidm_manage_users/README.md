# rhidm_manage_uses

This role manages users in an IdM domain.

## Handling of variables

Understanding how variables are handled is crucial.  
In the following sections we will describe how you can handle your users, groups
hostgroups and other variables.

### Users

Users are defined in one list: 

* rhidm_user_list

#### rhidm_user_list
In this list we store all the information of the users that will be created exactly as they are defined in it.

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
    - rhidm_manage_uses
```

## License
GPLv3

## Author Information 
Peter Tselios (ptselios@redhat.com)
