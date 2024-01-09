# Playbooks

## Run Playbook

To run playbook: `ansible-playbook run.yml`
If sudo requires password in host machine: `ansible-playbook run.yml -K`
If sensible credentials in vault are used: `ansible-playbook run.yml --ask-vault-pass`
