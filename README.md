# DEPRECATED: Longhorn_Node

***This role will be depreciated use the collection, [rmasters270.kubernetes](https://github.com/rmasters270/ansible-collection-kubernetes).***

Install Longhorn prereuisites for on a Kubernetes nodes.

[![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-longhorn_node-blue.svg)](https://galaxy.ansible.com/ui/standalone/roles/rmasters270/longhorn_node)

## Dependencies

Use this role in conjunction with the role, [rmasters270.longhorn](https://galaxy.ansible.com/ui/standalone/roles/rmasters270/longhorn).

## Example Playbook

```yaml
- hosts: k3s_nodes

  roles:
    - rmasters270.longhorn_node

- hosts: localhost

  roles:
    - rmasters270.longhorn
```

## License

MIT

## Author Information

Ryan Masters
