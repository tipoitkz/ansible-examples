# ansible-examples

>## Tags

```bash
ansible-playbook tasks.yml --tags="stop metricbeat"
ansible-playbook tasks.yml --tags="start metricbeat"
ansible-playbook tasks.yml --tags="start metricbeat" --list-tasks
ansible-playbook roles.yml --tags="start metricbeat"
ansible-playbook include_tasks.yml --tags="stop metricbeat"
ansible-playbook include_tasks_without_apply.yml --tags="stop metricbeat"
ansible-playbook always.yml --tags="start metricbeat"
ansible-playbook never.yml
```