# Kubernetes_etcd_cluser
Kubernetes cluster setup with etcd cluster

# Ansible module for kubernetes cluser with etcd
You can use and setup your Kubernetes cluster with etcd cluster.

# Component of this kubernetes Module.
## Inventory: 
            We are using hosts file in this module as a inventory. 
            [master]
            IP Address for Kubernet master server
            [etcd]
            IP Address for etcd serve r
            [node]
            IP Address for all cluster nodes
## Roles:
        We are using roles based structure...
        roles/
              etcd/
                  files/
                  templates/
                  vars/
                  tasks/main.yml
                  handlers/main.yml
                  meta/
                  
## Variables:
            We are using group variables in this module. For all roles we are using all.yml and define all the veriable in it.
            group_vars/
                      all.yml           
