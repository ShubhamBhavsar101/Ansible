Ansible Commands

1. Inventory file contents
```bash
192.168.1.13 ansible_user=ubuntu
```

3. Inventory file can be created in the same directory and can be used with
```bash
ansible -i inventory all -m "shell" -a "touch devopsclass"
```

3. 
