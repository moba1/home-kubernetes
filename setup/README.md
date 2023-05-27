Kubernetes host & cluster setup playbook

## Requirements

- [Ansible](https://www.ansible.com/)

## Quick Start

run following command

```bash
# use `sudo` in remote
ansible-playbook -i '<hostname>,'  playbook.yaml
# use `doas` in remote
ansible-playbook -i '<hostname>,' --become-method=doas playbook.yaml
```
