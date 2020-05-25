# Keycloak Ansible Playbook

Ansible playbook to deploy Keycloak 10.0.1 on Ubuntu 20 (Focal Fossa).

## Usage

- Setting host in ``/etc/ansible/hosts``

```` ini
[keycloak]
hostname
```` 

- Run playbook

```` console
$ ansible-playbook playbook.yml
````

- Entre username and password for keycloak administrator

## To Do

- [ ] Use certificate from let's encrypt
- [ ] Hardening systemd unit file
- [ ] Manage reboot after system upgrade (/var/run/reboot-required)
