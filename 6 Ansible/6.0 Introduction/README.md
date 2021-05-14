Ansible is a radically simple IT automation engine that automates cloud provisioning, configuration management, application deployment, intra-service orchestration, and many other IT needs.

Designed for multi-tier deployments since day one, Ansible models your IT infrastructure by describing how all of your systems inter-relate, rather than just managing one system at a time.

It uses no agents and no additional custom security infrastructure, so it's easy to deploy - and most importantly, it uses a very simple language (YAML, in the form of Ansible Playbooks) that allow you to describe your automation jobs in a way that approaches plain English.

For more detail... https://opensource.com/resources/what-ansible





https://docs.ansible.com/ansible/latest/index.html

https://www.jeffgeerling.com/blog/2020/ansible-101-jeff-geerling-youtube-streaming-series
good series of videos that breaks down ansible
From Ansible Docs:

*Ansible is an IT automation tool. It can configure systems, deploy software, and orchestrate more advanced IT tasks such as continuous deployments or zero downtime rolling updates.*

*Ansible’s main goals are simplicity and ease-of-use. It also has a strong focus on security and reliability, featuring a minimum of moving parts, usage of OpenSSH for transport (with other transports and pull modes as alternatives), and a language that is designed around auditability by humans–even those not familiar with the program.*

Ansible is owned by Redhat and is one of the open source tools that we employ to conduct configuration management and deployment of config changes. 

Our current use case for anisble is generating configuration files for our communication packages to include pushing or mailing the configs to the end user or device. Playbooks are also used to install and upgrade the automation tools we use.

The license dashboard and new TSOs will be implemented with it as well.
