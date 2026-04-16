# Ansible-srl-automation-lab

# Tech Stack
* Topology: containerlab
* Automation: ansible
* Network OS: Nokia SR Linux
* Client OS: alpine

# Network Topology

![topology](images/topo.png)

# How to Run

run containerlab
```
containerlab deploy -t containerlab/srlinux_lab.yml
```


run ansible
```
ansible-playbook -i ansible/inventory/hosts.yml ansible/playbook/control.yml
```

# reports

spine1
![topology](images/spine1.png)

spine2
![topology](images/spine2.png)

leaf1
![topology](images/leaf1.png)

leaf2
![topology](images/leaf2.png)