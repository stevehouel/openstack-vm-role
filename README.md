# OpenStack VM Creation playbook #


## Requirements

This project must be cloned under specific project's Ansible Roles to Create OpenStack VM.

## Variables

`cloudstack_auth_url` : CloudStack Authentication URL

`cloudstack_login` : CloudStack Login

`cloudstack_password` : CloudStack Password

`cloudstask_project` : CloudStack Tenant Name

`vm_state` : Set to "present" to create or check if VM exists, set it to "absent" to delete or check if VM dosn't exist

`vm_hostname` : VM name

`vm_image` : VM Image name or ID

`vm_flavor` : VM Flavor Name or ID

`vm_network` : VM subnet Name or ID

`vm_auto_ip` : Set to "yes" to get an Public IP or "no" to not

`vm_description` : VM Description

## Files

* You need to create a file with path `user_data_vm/user_data.sh` to include Cloud-init configurations.