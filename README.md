# ansible-srl-automation-lab

Tech Stack
* containerlab
* ansible
* Nokia SR linux


## containerlab
deploy topology
<pre>
containerlab deploy -t containerlab/2_srl.yml
</pre>

## ansible
run playbook
<pre>
ansible-playbook -i ansible/inventory.yml ansible/playbook/[name].yml
</pre>

### change_hostname.yml
Set the device hostname based on the inventory.yml