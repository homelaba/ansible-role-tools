# ansible-role-tools
Ansbile install tools to proxmox lxc

Create file `ansible/roles/requirements.yml`

```yaml
---
roles:
  - src: https://github.com/homelaba/ansible-role-tools.git
    name: install_tools
    version: main
    scm: git
```

Install command

```bash
ansible-galaxy role install -r ansible/roles/requirements.yml -p ansible/roles
```
