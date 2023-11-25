# Ansible Commands

```bash
# First command to test connection
ansible -i /mnt/automation/ansible/inventory/hosts ubuntu_2004 -m ping --user eweishaar --ask-pass

# setup SSH
ansible-playbook playbooks/ssh-setup.yml -i inventory/hosts --user eweishaar --ask-pass --ask-become-pass
```
