# Ansible Role: Ansible Essentials

This role is a helper for installing all ansible essentials.
Some ansible modules requires additional packages to be installed before module will work.


## Requirements

N/A


## Role Variables

Please look at: ``defaults/main.yml``
 

## Dependencies

N/A


## Installation

### Directly from ansible-galaxy (latest release)

```bash
$ ansible-galaxy install marcinpraczko.ansible_essentials
```

### Directly from github repository

Sometimes some changes has been applied to ``develop`` or ``featuremarcinpraczko.ansible_essentials`` branch and are not yet released.
Ansible-galaxy allows install roles directly from ``GitHub``.

```bash
ansible-galaxy install -p roles git+https://github.com/marcinpraczko/ansible-role-ansible_essentials.git,develop
```

Above example will install ``develop`` branch. This can be adjusted to any git SHA commit, tag or branch
name - depends of requirements.

Checking what version is installed can be done with command:
```bash
ansible-galaxy list -p roles
```


### Via Ansible-Galaxy in requirements.yml

```yaml
- src: marcinpraczko.ansible_essentials
  name: "marcinpraczko.ansible_essentials"
  version: 0.1.0
```

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: servers
  roles:
    - { role: "marcin.praczko.ansible_essentials" }
```


## License

MIT / BSD


## Author Information

Marcin Praczko
