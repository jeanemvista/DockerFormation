# Introduction
* Tavail au sein de [Penbase](https://www.penbase.com/) et d'[Emvista](https://www.emvista.com/).
* Cours et travaux pratiques en MIASH


<!--ts-->
* [Etat de l'art](#Etat-de-l'art)
	+ [Historique](#Historique)
	+ [La conteneurisation](#La-conteneurisation)
* [Docker](#Docker)
<!--te-->



# Etat de l'art


## Historique

En 2006 des ingénieurs de Google développe une fonctionnalité au kernel Linux permettant de compter, de limiter et d’isoler l’utilisation des resources (CPU, Mémoire, Disque, …). Elle sera intégrée à la version 2.6.24 du kernel : [cGroups](https://www.kernel.org/doc/Documentation/cgroup-v1/cgroups.txt) pour Control Groups. Cgroups permet d'isoler un simple processus ou de visrtualiser un système d'exploitation complet.
L'utilisation des espace de nommage (namespace) de Linux permet cette isolation.

En 2008, LXC (Linux Containers) est un système de virtualisation, utilisant le cloisonnement d’un environnement partageant le même noyau. LXC repose sur cgroups.

## La conteneurisation

Une VM ou Machine Virtuel virtualise un système d’exploitation complet afin d’exécuter un ou plusieurs processus.

VS

Un conteneur est une enveloppe virtuelle permettant d’embarquer “un processus logiciel” et ses dépendances.

# Docker

