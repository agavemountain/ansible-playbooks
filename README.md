# ansible-playbooks
Ansible playbooks

## Cheat Codes

### Update APT 
```
ansible-playbook ./playbooks/apt.yaml --user <USERNAME> --ask-pass --ask-become -i hosts
```

### Install developer tools
```
ansible-playbook ./playbooks/developer.yaml --user <USERNAME> --ask-pass --ask-become -i hosts
```