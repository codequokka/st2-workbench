ST2-WORKBENCH
=============

```console
# ansible-playbook -i inventories/usagi/hosts.ini playbooks/st2-testbench.yml --extra-vars='ansible_sudo_pass=<your_sudo_password>' --tags=setup

# ansible-playbook -i inventories/usagi/hosts.ini playbooks/st2-testbench.yml --extra-vars='ansible_sudo_pass=<your_sudo_password>' --tags=test
```
