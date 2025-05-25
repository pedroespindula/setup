# setup

This repository starts up a fresh installed Manjaro OS with the necessary dotfiles and applications.

## How to run

```shell
ansible-playbook -i inventory --ask-become-pass playbooks/install-apps.yaml
```
