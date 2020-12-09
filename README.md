# Configuring-hadoop-cluster-using-ansible
This is tested on Rhel VM
Before running playbook download all the files and keep in one directory, download jdk-8u171-linux-x64.rpm and hadoop-1.2.1-1.x86_64.rpm and keep in same directory
use cd to go the directory and then run hadoop playbook first then run nodes playbook
In your inventory keep IP to be configured as master node under group namenode and IP to be configured as slave node under group datanode
