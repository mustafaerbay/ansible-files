some links

https://docs.ansible.com/ansible/2.4/playbooks_best_practices.html


scp -r /drives/d/00erbay/projects/ansible root@10.243.231.38:/opt/ansible

### golang

**NOTES**: UPDATE roles/golang/golang_hosts.ini first
```
ansible-playbook roles/golang/main.yaml -i roles/golang/golang_hosts.ini
```

>[x] install

>[] uninstall

TODO:
- GOLANG: vars folder and files have to be added for different os

### docker

**NOTES**: UPDATE roles/docker/hosts.ini file first
```
ansible-playbook roles/docker/main.yaml -i roles/docker/docker_hosts.ini
```
> [x] install

> [x] uninstall

TODO:
- DOCKER: vars files has to be added for different os