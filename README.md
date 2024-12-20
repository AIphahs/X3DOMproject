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

## Utilisation
- Installez et configurez NGINX sur votre machine en suivant les instructions sur le site officiel : NGINX Installation.

- Placez le dossier du projet dans le répertoire de votre serveur NGINX (par défaut, /usr/share/nginx/html).

- Assurez-vous que le serveur NGINX est bien configuré pour servir les fichiers statiques (HTML, CSS, JS) et les modèles X3D.

- Accédez à votre site via un navigateur compatible en utilisant l'URL appropriée (par défaut, http://localhost:8080)

## Usage
Une fois le site en ligne :

Explorer les différentes vues possibles : Overview / Bathroom / Living Room / Bedroom / Guestromm / Kitchen
![Overview](https://github.com/user-attachments/assets/40649020-919f-4b57-ad3a-97c165f2d25c)

Explorer en 3D : L'utilisateur peut se déplacer librement dans la scène en mode "marche" ou utiliser les points de vue prédéfinis pour explorer l'environnement.
![Mouse view 1](https://github.com/user-attachments/assets/6df5402d-bf52-46c2-b08f-49f0da259b53)
![Mouse view 2](https://github.com/user-attachments/assets/5afa71a3-0120-4ec9-a537-bb26f21d5cb7)
![Mouse view 3](https://github.com/user-attachments/assets/b99f7144-346e-4a89-bff6-424a8d56450d)
![Mouse view 4](https://github.com/user-attachments/assets/38779d61-fd6f-4296-91e6-98feef36f531)


Afficher des informations : En cliquant sur des objets ou équipements dans la scène 3D, des informations supplémentaires apparaîtront.
![Clicked](https://github.com/user-attachments/assets/49f3f648-2743-4fe4-86e6-548d2c9ce31f)

## Sources
Environnement 3D : https://sketchfab.com/3d-models/house-interior-448be2ae6a164542a6316113411a3e83
Documentation x3Dom : https://examples.x3dom.org/simpleExamples.html


