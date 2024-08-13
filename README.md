# Test Case - Server Preparation playbook

Playbook prepares the server by encrypting disks, disabling C-state, switching CPU mode, renaming network interfaces, and displaying CPU and Hyper-Threading information.

## How to Use

1. Modify the inventory file `inventory` with target hosts
2. Update path to ssh key in `ansible.cfg`
3. Run the playbook: ansible-playbook playbook.yml
