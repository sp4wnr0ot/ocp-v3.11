# Ansible Inventory File - Demo 

OpenShift installation 3.11.104 inventory file as an example 

Red Hat Enterprise Linux 7.6 + Ansible


# OpenShift v3.11.104 - Deploy

Use this inventory file as an example to deploy ocp v3.11.104 for tests in non production environment.

DON'T FORGET to change hosts, passwords, proxy, domain, hostname and storage setup.

Token generation

https://access.redhat.com/terms-based-registry/

## Usage
Once all pre reqs were configured, by official ocp documentation
execute the ansible playbook.

https://docs.openshift.com/container-platform/3.11/install/prerequisites.html

$ sudo ansible-playbook -i hosts-ocp-v3.11.104 /usr/share/ansible/openshift-ansible/playbooks/prerequisites.yml

$ sudo ansible-playbook -i hosts-ocp-v3.11.104 /usr/share/ansible/openshift-ansible/playbooks/deploy_cluster.yml


