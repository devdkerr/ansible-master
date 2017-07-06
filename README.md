# Ansible Master

Docker container for administrating Ansible targets.

For example to run a module on all configured remote hosts, run the following:

```
docker run --rm devdkerr/ansible-master ansible all -m ping
```
