# Ansible-srl-automation-lab

Tech Stack
* containerlab
* ansible
* Nokia SR linux


# How to run
## containerlab
deploy topology
<pre>
containerlab deploy -t containerlab/3_srl.yml
</pre>

## Ansible
run playbook
<pre>
ansible-playbook -i ansible/inventory.yml ansible/playbook/[name].yml
</pre>

### config ip address