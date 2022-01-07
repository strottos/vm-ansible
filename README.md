To run, find a Linux machine with Ansible on it (can be a docker container maybe) and run the following on first run on the machine:
```
ansible-galaxy collection install community.general
```

Now edit the hosts.cfg file appropriately and run:
```
ansible-playbook master.yaml
```
