# Laradock

[![forthebadge](http://forthebadge.com/images/badges/built-by-developers.svg)](http://zalt.me)

[![Gitter](https://badges.gitter.im/LaraDock/laradock.svg)](https://gitter.im/LaraDock/laradock?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

Laradock is a Docker PHP development environment. It facilitate running **PHP** Apps on **Docker**. 

Laradock is configured to run Laravel Apps by default, and it can be modified to run all kinds of PHP Apps (Symfony, CodeIgniter, Wordpress, Drupal...).

>Use Docker first and learn about it later.

**Zie (https://github.com/laradock/laradock) voor de originele README**

## Installatie
* Clone of download deze repo naar `C:/workspace/laradock`
* gebruik het volgende command om te meestgebruikte containers te starten:
`docker-compose -f production-docker-compose.yml up -d`

## Getest op:
### Docker Toolbox + VirtualBox 5.1.26 i.c.m. Boot2Docker:
* `Docker version 17.05.0-ce, build 89658be`
* `docker-compose version 1.12.0, build ee0f34e1`
* `docker-machine.exe version 0.11.0, build 5b27455`

### Docker for Windows:
* `Docker version 18.09.0`
* `docker-compose version 1.23.1`
* `docker-machine.exe version 0.16.0`

## Workspace
Deze versie verwacht dat je git repos in de map: `C:/workspace` staan. Dit kan je aanpassen in de `production-docker-compose.yml` file

## HOSTS
De volgende hosts zijn in ieder geval ingesteld om te resolven in nginx:
* mercury.io
* krypton.io
* workspace.panelinzicht.nl
* tabulation.io