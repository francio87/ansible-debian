```
ansible-playbook -i 10.10.10.10, debian.yml -u admin --ask-pass --ask-become-pass -e 'ansible_ssh_common_args="-o StrictHostKeyChecking=no" ansible_ssh_port=22'
```
