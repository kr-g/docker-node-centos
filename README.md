# docker-node-centos

centos with nodejs, npm and n

can be used as base for own centos images 

# supported versions

## os version

currently centos 7 only

## all node version 

the base comes from rhel package epel-release 

use the n command in your own derived dockerfile to setup the required version of nodejs

### dockerfile sample code to install any node version 

    FROM anothersoftwaredevelopmentblog/docker-node-centos:centos7
    ...
    RUN n {node-version}


## image available on docḱer hub

https://hub.docker.com/r/anothersoftwaredevelopmentblog/docker-node-centos/
