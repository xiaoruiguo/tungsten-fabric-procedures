Tungsten-fabric procedures
====

This repository is aimed at uploading Tungsten-fabric install procedure.
In addition, We prepare multiple use cases so that more people can experience Tungsten-fabric.

## Description

The procedure in this repository is deployed using [contrail-ansible-deployer] (https://github.com/Juniper/contrail-ansible-deployer) in the Juniper Networks repository.

The tools used for deployment are Ansible and OpenStack kolla.

Because you are using OpenStack kolla, you can quickly deploy using Docker Container.

We will deploy using the following two docker repositories.
   - [https://hub.docker.com/u/kolla/](https://hub.docker.com/u/kolla/) 
   - [https://hub.docker.com/u/kolla/](https://hub.docker.com/u/opencontrailnightly/)

Each repository is daily build, so the latest version will always be deployed.

Also, if you want to fix the version, you need to build a local repository.

**At the moment OpenStack Ocata + Contrail 5.1 will be deployed**

We upload steps individually for each use case.

## Use Case
### 1. ALL in One Deploy
[01_All_in_One](https://github.com/konono/tungsten-fabric-procedures/blob/master/01_All_in_One.md)

## Licence

[MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)

## Author

[tcnksm](https://github.com/tcnksm)
