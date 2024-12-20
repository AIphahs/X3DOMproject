# Projet de Navigation et Consultation d'un Bâtiment

## Description

Ce projet consiste en la création d'un site internet permettant de naviguer et de consulter un bâtiment ou une installation (maison, immeuble, navire, usine, site industriel, etc.) via une maquette 3D interactive et une carte 2D. Le site utilise la technologie X3DOM pour afficher des modèles 3D dans le navigateur (Google Chrome/Mozilla Firefox/Opera) et un serveur web NGINX pour l'hébergement.

### Fonctionnalités principales :

- **Affichage du plan 2D** : Un plan ou une carte du bâtiment ou de l'installation, permettant à l'utilisateur de naviguer dans différentes zones (salles, couloirs, routes, etc.).
- **Navigation 3D** : Lorsque l'utilisateur clique sur une zone du plan 2D, il est redirigé vers la maquette pièce correspondante.
- **Informations interactives** : En cliquant sur des objets ou équipements dans la scène 3D, l'utilisateur peut afficher des informations (metadata X3D ou externes) concernant ces objets.
- **Mode "Marche" et points de vue prédéfinis** : L'utilisateur peut se déplacer librement dans la scène en mode "marche" ou cliquer sur des points de vue prédéfinis pour explorer l'installation.
- **Navigation entre le plan 2D et la maquette 3D** : L'interface utilisateur (IHM) permet de passer de manière fluide entre la carte 2D et la vue 3D.

## Prérequis

- **Technologies utilisées** :
  - **X3DOM** pour l'affichage 3D dans le navigateur.
  - **NGINX** comme serveur web.
  - **HTML/CSS/JavaScript** pour l'interface utilisateur.
  - **Docker Desktop** (Pour le serveur web Nginx, Optionnel)

- **Navigateur** : Google Chrome / Mozilla Firefox / Opera...

- **Serveur** : NGINX (vous pouvez installer et configurer NGINX pour servir le site web localement ou sur un serveur distant).

## Installation

1. Clonez ce dépôt sur votre machine locale :
   ```bash
   git clone https://github.com/AIphahs/X3DOMproject.git
