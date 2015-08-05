## MariaDB server on Ubuntu 14.04

[![Docker Hub; nimmis/mariadb](https://img.shields.io/badge/dockerhub-nimmis%2Fmariadb-green.svg)](https://registry.hub.docker.com/u/nimmis/mariadb)

## What is MariaDB?

MariaDB is a community-developed fork of the MySQL relational database management system intended to remain free under the GNU GPL.


Container based on [![Docker Hub; nimmis/ubuntu](https://img.shields.io/badge/dockerhub-nimmis%2Fubuntu-green.svg)](https://registry.hub.docker.com/u/nimmis/ubuntu) with working init process and syslog. For more information on how to set upp services, please read the dockumentation for [nimmis/ubuntu](https://registry.hub.docker.com/u/nimmis/ubuntu)


## Starting the container

To run the lastest stable version of this docker image run

	docker run -d nimmis/mariadb

to expose the database to the external interface run

	docker run -d -p 3306:3306 nimmis/mariadb



