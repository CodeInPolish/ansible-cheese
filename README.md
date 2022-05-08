# ansible-cheese
Ansible playbooks to configure all devices in my homelab

## First setup
Manually add your pub key to the user on the host in `.ssh/authorized_keys`

Launch `00_initial_setup.yml` with the following parameters:
`--user <user> --ask-become-pass --ask-pass` 