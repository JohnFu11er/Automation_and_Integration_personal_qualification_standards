From Ansible Docs:

*Ansible is an IT automation tool. It can configure systems, deploy software, and orchestrate more advanced IT tasks such as continuous deployments or zero downtime rolling updates.*

*Ansible’s main goals are simplicity and ease-of-use. It also has a strong focus on security and reliability, featuring a minimum of moving parts, usage of OpenSSH for transport (with other transports and pull modes as alternatives), and a language that is designed around auditability by humans–even those not familiar with the program.*

Ansible is owned by Redhat and is one of the open source tools that we employ to conduct configuration management and deployment of config changes. 

Our current use case for anisble is generating configuration files for our communication packages to include pushing or mailing the configs to the end user or device. Playbooks are also used to install and upgrade the automation tools we use.

The license dashboard and new TSOs will be implemented with it as well.