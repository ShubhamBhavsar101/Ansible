## Ansible Modules
Search "**Ansible Modules**" on Google and go to "**All Modules**"

- shell – Execute shell commands on targets


## Ansible Commands

1. Inventory file contents
```bash
192.168.1.13 ansible_user=ubuntu
```

2. Inventory file can be created in the same directory and can be used with
```bash
ansible -i inventory all -m "shell" -a "touch devopsclass"
```

3. 
