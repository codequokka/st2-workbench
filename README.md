ST2-WORKBENCH
=============
```console
# dnf install -y python38
# pip3.8 install -y pipenv
```

```console
# ansible-playbook -i inventories/usagi/hosts.ini playbooks/st2-testbench.yml --extra-vars='ansible_sudo_pass=<your_sudo_password>' --tags=setup

# ansible-playbook -i inventories/usagi/hosts.ini playbooks/st2-testbench.yml --extra-vars='ansible_sudo_pass=<your_sudo_password>' --tags=test
```
