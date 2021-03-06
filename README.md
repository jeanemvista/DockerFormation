# Introduction

Vous travaillez sur un projet de fin d'étude et vous venez de passer plusieurs jours/nuits à développer votre application. Celle-ci marche parfaitement bien et vous êtes prêt à la présenter. Vous déployez votre application sur l'ordinateur d'un collègue et là votre application ne démarre pas à cause d'une version trop ancienne d'une dépendance. Si vous aviez mis votre application et ses dépendances dans un conteneur vous n'auriez pas eu ce souci.

Vous trouverez ici le fruit de mon travail :
* au sein de [Penbase](https://www.penbase.com/) et d'[Emvista](https://www.emvista.com/).
* pour des cours et travaux pratiques en MIASH


<!--ts-->
* [Etat de l'art](#Etat-de-l'art)
	+ [Historique](#Historique)
	+ [La conteneurisation](#La-conteneurisation)
* [Docker](#Docker)
<!--te-->

# Etat de l'art


## Mots clés

Espace de nom, conteneur, virtualisation, resoures, processus,

## Bibliographie

* https://www.kernel.org/doc/Documentation/cgroup-v1/cgroups.txt
* http://pf-mh.uvt.rnu.tn/1009/


## Historique

Dés 1998, sur les systèmes Unix, il était possible d'isoler un processus  avec ```chroot``` 

En 2006, des ingénieurs de Google développe une fonctionnalité au kernel Linux permettant de compter, de limiter et d’isoler l’utilisation des resources (CPU, Mémoire, Disque, …). Elle sera intégrée à la version 2.6.24 du kernel : [cGroups](https://www.kernel.org/doc/Documentation/cgroup-v1/cgroups.txt) pour Control Groups. Cgroups permet d'isoler un simple processus ou de virtualiser un système d'exploitation complet.
L'utilisation des espaces de nommage (namespace) de Linux permet cette isolation.

En 2008, LXC (Linux Containers) est un système de virtualisation, utilisant le cloisonnement d’un environnement partageant le même noyau. LXC repose sur cgroups..

## La conteneurisation

Une VM ou Machine Virtuel virtualise un système d’exploitation complet afin d’exécuter un ou plusieurs processus.

VS

Un conteneur est une enveloppe virtuelle permettant d’embarquer “un processus logiciel” et ses dépendances.

# Docker


# notes personnelles et/ou idées
La conteneurisation et les modèles d'inteligence artificielle.