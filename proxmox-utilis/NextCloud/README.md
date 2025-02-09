# FR

## Intro
Nextcloud est un cloud open source permettant d'héberger les données d'un ou de plusieurs utilisateurs. L'avantage majeur de ce cloud, en plus de sa légèreté, est son hébergement local, ce qui signifie que nous sommes les seuls responsables de nos données, que ce soit pour leur traitement ou pour prévenir d'éventuelles fuites. Pour minimiser les risques de cyberattaques, il est conseillé de sécuriser ce cloud et de l'intégrer dans une infrastructure cohérente, par exemple en le plaçant dans une DMZ, en le protégeant par un pare-feu et, si possible, en utilisant des logiciels tels que CrowdSec ou encore des systèmes IPS/IDS. Il peut même être pertinent de restreindre l'accès à Nextcloud via un VPN.

## Installation

Pour installer ce logiciel, nous allons utiliser Docker, qui nous permettra de déployer rapidement notre solution. Pour cela, vous trouverez dans le fichier `docker-compose.yaml` la configuration Docker Compose de Nextcloud.

## Fonctionnalités

En termes de fonctionnalités, Nextcloud vous permet de stocker vos dossiers, vos images et vos fichiers personnels dans un espace sécurisé. Il est possible de mettre en ligne votre instance Nextcloud afin d'y accéder de n'importe où et à tout moment. Pour cela, je vous recommande de consulter mon tutoriel expliquant comment exposer vos services en ligne.

# EN

## Introduction

Nextcloud is an open-source cloud solution that allows one or multiple users to host their data. One of its key advantages, besides its lightweight nature, is that it is self-hosted, meaning we have full control over our data, both in terms of processing and potential leaks. To minimize the risk of cyberattacks, it is recommended to secure this cloud and integrate it into a well-structured infrastructure—placing it in a DMZ, protecting it with a firewall, and, if possible, using security tools such as CrowdSec or IPS/IDS systems. It may even be necessary to restrict access to Nextcloud exclusively through a VPN.

## Installation

To install this software, we will use Docker, which allows us to deploy our solution quickly. For this, you can find the Nextcloud Docker Compose configuration in the `docker-compose.yaml` file.

## Features

Regarding features, Nextcloud enables you to store your folders, images, and personal files in a secure environment. You can also make your Nextcloud instance accessible online, allowing you to reach it anytime and anywhere. If you're interested in doing so, I recommend checking out my tutorial on exposing your services online.
