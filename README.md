# ansible-k3s
## Playbooks:
 * update - `apt update`
 * upgrade - `apt upgrade`

## How to run
Run for all hosts:
```shell
ansible-playbook -i inventory/inventory.yaml playbooks/PLAYBOOK_NAME.yaml -K
```

Run for specific host:
```shell
ansible-playbook -i inventory/inventory.yaml --limit HOSTNAME playbooks/PLAYBOOK_NAME.yaml -K
```
