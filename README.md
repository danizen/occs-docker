# occs-docker

Ansible role to installs docker-ce on CentOS 7
Variables control which version to install and whether edge 
and testing should be enabled

## Note on maintenance

For security, the following have been copied

 - https://download.docker.com/linux/centos/docker-ce.repo
 - https://download.docker.com/linux/centos/gpg

The gpg key is renamed DOCKER-RPM-KEY and the repository is modified
to point to the key.

## Status

Not yet implemented - not ready to use
