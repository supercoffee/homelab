# Ben's Homelab


## Running ansible playbooks

### Dependencies

```shell

ansible-galaxy collection install community.docker

```

Use the docker-host playbook located in `ansible/docker-host` to provision the docker host

```shell

ansible-playbook -i inventory.yml playbook.yml
```

## Todos

* 
