# singularity-docker-centos7-warewulf4-builder [![Docker and Singularity build](https://github.com/truatpasteurdotfr/singularity-docker-centos7-warewulf4-builder/actions/workflows/docker-singularity-publish.yml/badge.svg)](https://github.com/truatpasteurdotfr/singularity-docker-centos7-warewulf4-builder/actions/workflows/docker-singularity-publish.yml)
warewulf4 builder container based on a CentOS 7 x86_64 docker image  built from github actions

Tru <tru@pasteur.fr>

## Why?
- provide a minimal builder for warewulf4

## Caveat
- playground, use at your own risk!

## Docker
```
docker run -ti ghcr.io/truatpasteurdotfr/singularity-docker-centos7-warewulf4-builder:main
```
## Singularity
```
singularity exec oras://ghcr.io/truatpasteurdotfr/singularity-docker-centos7-warewulf4-builder:latest rpmbuild -ta warewulf-4.2.0.tar.gz 
```
