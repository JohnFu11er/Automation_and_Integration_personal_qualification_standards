[Ansible Install Guide](https://docs.ansible.com/ansible/latest/installation_guide/index.html)

We typically use RHEL or CENTOS to develop on since that is what we use in production. To install on RHEL or CENTOS simply enter the following command.

*sudo yum install ansible*

The majority of exams and training recommend that you install ansible in a python env. You can do that with the following commands:

    $ python -m virtualenv ansible  # Create a virtualenv if one does not already exist
    $ source ansible/bin/activate   # Activate the virtual environment
    $ python -m pip install ansible

You might get an error that the module virtualenv does not exist. If that happens install it with pip then proceed.

*pip3 install virtualenv*

We employ the current basic directory structure but you can use whatever you like or follow [ansible best practices](https://docs.ansible.com/ansible/2.8/user_guide/playbooks_best_practices.html#directory-layout)
Ansible Directory Structure:
    
    /etc/ansible
        /playbooks
            /global_vars
                enclave.yml
            /templates
                mfs_router.j2
            /roles
                /tasks
                    main.yml
            ssh_push.yml
        hosts
        inventory.py
        ansible.cfg

### Tips:
1. If you receive the following error when running a playbook *""msg": "Aborting, target uses selinux but python bindings (libselinux-python) aren't installed!"}"* Install selinux in your virtualenv. 
2. If you are constantly having to sudo when modifying files in your /etc/ansible directory you can do a *chwon -R user:group /etc/ansible* to give ownership of the dir structure to you and a specified group. This is typcially the wheel group in a rhel/centos OS.