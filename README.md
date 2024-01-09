# Ansible

## Host Machine Setup

### Install Ansible
`sudo apt install -y ansible`

### Define target machines
Define `hosts` file (where host and targets machine are defined), and create `ansible.cfg` which will target that file.

### Test connection
`ansible <GROUP> -i <INVENTORY_FILE> -m <MODULE>`
`ansible proxy -i hosts_with_proxy -m ping`

### Install modules
https://docs.ansible.com/ansible/latest/galaxy/user_guide.html

`ansible-galaxy collection install confluent.platform`

`ansible-galaxy collection install git+https://github.com/confluentinc/cp-ansible.git`

### Roles, Handlers, Ansible Galaxy, Filters & Loops
https://www.youtube.com/watch?v=SvcOwBFLVLM