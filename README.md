# Projet-Bts-Mobile

## Contexte

### Description
Le serveur est développé en **Java** avec **Processing** et utilise la librairie **WebSocket** pour gérer la communication en temps réel avec le client.
Le client est développer en Javascript et utilise la librairie p5.js pour afficher des éléments en 3d sur l'interface.

### Infos
Plus d'info sur le projet dans le rapport de projet.

---

## Prérequis
- [Processing](https://github.com/processing/processing4/releases/download/processing-1307-4.4.7/processing-4.4.7-windows-x64.msi) (version 4.4.7 ou inférieur)
- Librairie **WebSocket for Processing**

---

## Installation & Lancement
### 1. Cloner le projet
```bash
    git clone https://github.com/MateoDubernet/Projet-Bts-Mobile.git
```

### 2. Serveur
1. Ouvrir le dossier de l'application
2. Ouvrir le fichier ./backend/serveurJava.pde avec procesing
3. Dans Processing aller sur : `Sketch > Import Library > Manage Libraries...`
4. Rechercher `WebSocket`
5. Installer la librairie **WebSocket for Processing**
6. Cliquer sur le bouton play de processing

### 3. Client
1. Ouvrir le dossier de l'application
2. Ouvrir le fichier ./frontend/index.html dans le navigateur
3. Cliquer sur le bouton **ON/OFF** pour établir ou non la connexion avec le serveur et faire fonctionner le logiciel

---

## Fonctionnalités
Il y a 2 possibilités :
1. Manipuler les sliders pour faire bouger les barres et faire variers les vitesses qui s'affichent sur l'interface côté serveur
2. Sélectionner un motif neutre/sinus1/sinus2 pour faire bouger les barres de manières automatique





















