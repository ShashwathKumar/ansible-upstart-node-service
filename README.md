Ansible - Upstart node.js service
=================================

Ansible playbook for setting up 1 or more node processes to be managed as
upstart services on any number of Ubuntu machines.

## Usage

1. Rename inventory.example to inventory and fill in server details
2. Edit main.yml to taste, especially the projects variable
3. From the command line run `ansible-playbook --ask-sudo-pass -i inventory main.yml`

## Result

Once setup, you will be able to run 
`service my-super-node-service start|stop|restart` on the target machines
