# CASTLE's Project Documentation

**CASTLE** is **C**ontainerized **A**nsible **S**oftware and **T**ools **L**earning **E**xperience

It's actually a Docker Stack with:
* ElasticSearch / Logstash / Kibana / Filebeat
* Vault
* Gitlab CE
* Mattermost
* Ansible

Tested on Ubuntu:

```shell
$ cat /etc/lsb-release
DISTRIB_ID=Ubuntu
DISTRIB_RELEASE=18.04
DISTRIB_CODENAME=bionic
DISTRIB_DESCRIPTION="Ubuntu 18.04.1 LTS"

$ docker --version
Docker version 17.12.1-ce, build 7390fc6

$ docker-compose --version
docker-compose version 1.22.0, build f46880fe
```