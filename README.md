# Domo - Ansible

Useful Ansible roles to use in home automation setup

## Install dependencies

```
ansible-galaxy install -r requirements.yml
```

## Run Playbooks

```
ansible-playbook -i inventory -e @secrets.yaml monitoring.yaml
```