# Ansible Vars

## Sensible vars
Create new secret file: `ansible-vault create secret.yml`
Or encrypt an existing file `ansible-vault encrypt secret.yml`

## Test vars
`ansible <GROUP> -i <INVENTORY_FILE> -a "echo {{VARIABLE}}"`