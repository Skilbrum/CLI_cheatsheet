# UNIX

## CentOS

## Ububntu, Debian
### Install Docker CLI
apt-get install software-properties-common
curl -fsSL https://download.docker.com/linux/debian/gpg |apt-key add -
add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/debian $(lsb_release -cs) stable"
apt-get update
apt-get install docker-ce-cli
