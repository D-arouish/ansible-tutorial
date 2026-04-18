# ansible-tutorial

This repository contains Ansible tutorial exercises that I used to practice playbooks, inventories, file distribution, and repeatable server setup.

## Contents

- `inventory` for target hosts
- `playbook-01.yml` to `playbook-12.yml` for progressive examples
- `files/` and `ansible-nginx-demo/` for supporting resources

## Focus

- understanding playbook structure
- practicing host targeting and variables
- learning how Ansible can automate common administration tasks

## Run Locally

```bash
git clone https://github.com/D-arouish/ansible-tutorial.git
cd ansible-tutorial
ansible-playbook -i inventory playbook-01.yml -u REMOTE_USER
```

Use `-K` when the playbook needs elevated privileges.

## Notes

This repository is meant for learning and experimentation. It is a good reference set for basic Ansible patterns before moving to larger automation projects.
