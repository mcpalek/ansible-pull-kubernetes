# ansible-pull-kubernetes

With this playbook you can install Kubernetes on one server for the specific Linux type of distros as below:

This works for Ubuntu , CentOS ,RedHat and Rocky.

Hosts contains the server names or ip adresses , you should change it acording to your own needs.

In group_vars folder is file "all" where you can change the version of kubernetes you want to install

there you will find "rocky_kubernetes_version: 1.31.1" this is for all RedHat based distros

"ubuntu_kubernetes_version: 1.31.1-1.1" for all Ubuntu versions

"repo_version: v1.31" this is the same for all distros

Before starting this playbok , you must install Ansible on that server.

command should be used as ROOT user like this:

ansible-pull -U https://github.com/mcpalek/ansible-pull-kubernetes.git



