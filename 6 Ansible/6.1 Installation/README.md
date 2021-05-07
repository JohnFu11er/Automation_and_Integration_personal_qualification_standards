[Ansible Install Guide](https://docs.ansible.com/ansible/latest/installation_guide/index.html)

We typically use RHEL or CENTOS to develop on since that is what we use in production. To install on RHEL or CENTOS simply enter the following command.

*sudo yum install ansible*

The majority of exams and training recommend that you install ansible in a python env. You can do that with the following commands:

    $ python -m virtualenv ansible  # Create a virtualenv if one does not already exist
    $ source ansible/bin/activate   # Activate the virtual environment
    $ python -m pip install ansible

You might get an error that the module virtualenv does not exist. If that happens install it with pip then proceed.

*pip3 install virtualenv*
