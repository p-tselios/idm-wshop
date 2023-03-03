# rhidm_configure

This role configures a Red Hat IdM server.

This role will:

* Perform the initial configuration of IDM

## Handling of variables

Understanding how variables are handled is crucial.  
In the following sections we will describe how you can handle your users, groups
hostgroups and other variables.

## Requirements

* A running Red Hat IDM / FreeIPA server
* [FreeIPA Ansible collection](https://github.com/freeipa/ansible-freeipa) installed
* Ansible 2.9+
* Jinja 2.10+

## Role Variables

Please refer to the [defaults/main.yml](defaults/main.yml) for a detailed description of the variables used in this role.

## Dependencies

None

## Example Playbook

```yaml
---
- name: Create RH IDM content
  hosts: rhidms_master
  roles:
    - rhidm_configure
```

## License

## Author Information 
Peter Tselios (ptselios@redhat.com)
