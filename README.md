# CentOS with ansible

CentOS 7 with ansible to run recipies

## Run ansible from Docker
The entrypoint for this container is /usr/bin/ansible so mount your ansible configuration in /etc/ansible and run ansible with:

```bash
docker run -ti vrdominguez/centos-ansible <params>
```

## Launch the container in bash mode
If you want to access bash in the container, just run:

```bash
docker run -ti --entrypoint /bin/bash vrdominguez/centos-ansible
```
