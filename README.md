# Reaction Test - Le Test de Réaction Surprenant !

![Bannière de l'application](https://github.com/thiersY/reactionTest/blob/main/icon.png)

## Table des matières

* [Introduction](#introduction)
* [Fonctionnalités](#fonctionnalités)
* [Le "Screamer Prank" ! (Avertissement)](#le-screamer-prank--avertissement)
* [Comment jouer](#comment-jouer)
* [Installation](#installation)
* [Captures d'écran](#captures-décran)
* [Technologies Utilisées](#technologies-utilisées)
* [Auteur](#auteur)
* [Licence](#licence)

## Introduction

Bienvenue sur **Reaction Test**, une application Android simple mais amusante conçue pour tester votre temps de réaction ! Mesurez votre rapidité à réagir à un signal visuel, et essayez de battre votre meilleur score. Mais attention... cette application cache une fonctionnalité inattendue et surprenante pour pimenter l'expérience !

## Fonctionnalités

* **Test de Réaction Classique :** Mesurez votre temps de réaction avec des feux de signalisation de course traditionnels (rouge > vert).
* **Affichage du Meilleur Score :** Suivez vos progrès et tentez de battre votre record personnel.
* **Interface Intuitive :** Un design clair et facile à utiliser.
* **"Screamer Prank" Intégré :** Une blague inattendue et surprenante conçue pour piéger les joueurs trop impatients (voir avertissement ci-dessous).
* **Avertissement Intégral :** Un écran de disclaimer s'affiche au démarrage pour prévenir les utilisateurs sensibles.
* **Menu d'Options :** Accédez à l'aide et aux informations "À propos" via un menu en haut à droite.

## Le "Screamer Prank" ! (Avertissement)

**Veuillez lire attentivement ceci avant d'utiliser l'application ou de la partager !**

Cette application contient un élément sonore et visuel conçu pour surprendre le joueur. Ce "screamer" est une blague et peut être intense pour certaines personnes.

**Fonctionnement du déclenchement du screamer :**

1.  Lancez un test de réaction.
2.  Si vous tapez sur l'écran *trop tôt* (avant que les lumières ne deviennent vertes), le message "Trop tôt !" s'affichera.
3.  À partir de ce moment-là, si vous cliquez **3 fois rapidement** sur le bouton "Rejouer" (dans un intervalle de 200ms à 10 secondes après l'affichage de "Trop tôt !"), le screamer se déclenchera !

**Recommandations :**

* **Ne pas utiliser** avec des personnes ayant des problèmes cardiaques, de l'épilepsie, ou qui sont facilement effrayées.
* **Ne pas utiliser** avec de jeunes enfants.
* Utilisez cette fonctionnalité de manière responsable et avec discernement.

## Comment jouer

1.  **Lisez l'avertissement :** Au premier lancement, un avertissement important s'affiche.
2.  **Lancez le test :** Cliquez sur le bouton "Démarrer le test".
3.  **Attendez le signal :** Les lumières deviendront rouges une par une, puis, après un délai aléatoire, elles passeront au vert.
4.  **Réagissez :** Dès que les lumières passent au vert, tapez l'écran le plus vite possible !
5.  **Obtenez votre score :** Votre temps de réaction s'affichera.
6.  **Rejouez :** Cliquez sur "Rejouer" pour tenter d'améliorer votre score.

## Installation

Pour installer et exécuter ce projet localement, suivez ces étapes :

1.  **Cloner le dépôt :**
    ```bash
    git clone [https://github.com/rojolalaina/ReactionTest.git](https://github.com/rojolalaina/ReactionTest.git)
    cd ReactionTest
    ```
2.  **Ouvrir dans Android Studio :**
    Ouvrez le projet dans Android Studio (Fichier > Ouvrir, puis sélectionnez le dossier `ReactionTest`).
3.  **Synchroniser Gradle :** Laissez Gradle synchroniser les dépendances.
4.  **Exécuter sur un émulateur ou un appareil :**
    Cliquez sur le bouton "Run" (le triangle vert) dans Android Studio pour déployer l'application sur un émulateur ou un appareil Android connecté.

## Captures d'écran

| Écran de Démarrage | Écran de Jeu  | Menu "À propos" |
| :-----------------: | :----------: | :-------------: |
| ![Screenshot 1](https://github.com/thiersY/reactionTest/blob/main/Screenshot_launch.png) | ![Screenshot 2](https://github.com/thiersY/reactionTest/blob/main/main.png) | ![Screenshot 3](https://github.com/thiersY/reactionTest/blob/main/a%20propos.png) |

## Technologies Utilisées

* **Kotlin**
* **Jetpack Compose** (pour l'UI moderne d'Android)
* **Gradle** (système de build)


## Auteur

**Ramisiharisoa R. Thierry**

* [Mon profil Facebook](https://www.facebook.com/rrthierry)

## Licence

Ce projet est sous licence GPL.

---
