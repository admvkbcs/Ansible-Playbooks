# KuberInstall
Ansible playbook to install Kubernetes cluster on **Ubuntu 18.04**

Can be installed on any number of nodes.

CNI - flannel

The list of hosts is in the file [hosts.ini](https://git.vkbcs.com/jd/ansible-playbooks/-/blob/master/Kubernetes/InstallCluster/hosts.ini)

Before starting the deployment, you need to enter your ip and hostnames there.

Useful for a simple cluster for tests.

After completing the task, the connection string for connect the working nodes to the cluster will be shown at the end.

It will have to be started manually on all nodes, except master node.

After that, you can check the operation of the cluster:

`kubectl get nodes`
