ST2-WORKBENCH
=============
```console
# dnf install -y python38
# pip3.8 install -y pipenv
```

```console
# ansible-playbook -i inventories/usagi/hosts.ini playbooks/st2-testbench.yml --tags=setup
# ansible-playbook -i inventories/usagi/hosts.ini playbooks/st2-testbench.yml --tags=test
```
