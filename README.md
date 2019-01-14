# docker-bench-security-ansible
Ansible playbook for configuring a Docker host according to security best practices (Docker Bench)

## Run
```
ansible-playbook docker_bench.yml -i hosts
```

## Inventory
```
[new_docker_hosts]
10.200.0.1
10.200.0.2
```
