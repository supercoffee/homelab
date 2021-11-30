# Ben's Homelab


## Running ansible playbooks

Use the docker-host playbook located in `ansible/docker-host` to provision the docker host

```shell

ansible-playbook -i inventory.yml playbook.yml
```

