
Distributeur Automatique de Médicaments - Projet Lycée
==============================================================

Ce projet consiste à concevoir un système automatisé de **distribution de médicaments**.
Il s’inscrit dans un cadre pédagogique de travaux pratiques en architecture et logique numérique.

Objectif du Projet
------------------

Développer une machine capable de distribuer un médicament à un utilisateur via un système logique,
en prenant en compte les différentes conditions (authentification, sélection, disponibilité).

Contenu du Projet
-----------------

1. Étude fonctionnelle et logique du système
2. Schéma logique de la machine (portes logiques, bascules, etc.)
3. Application de la **table de Karnaugh** pour la simplification des expressions logiques
4. Liste des composants utilisés (avec liens fournisseurs)
5. Simulation numérique et/ou réalisation physique (breadboard ou logiciel comme Logisim)

Exemple de Fonctionnement
--------------------------

- L’utilisateur sélectionne un médicament
- Le système vérifie la disponibilité
- La machine déclenche le mécanisme de distribution
- Affichage d’un état ou d’un message (ex : “Médicament distribué”)

Tableau de Karnaugh
--------------------

Utilisé pour optimiser la logique combinatoire. Il permet de réduire les expressions booléennes
nécessaires à l’activation du mécanisme de distribution.

Un exemple de simplification :
Entrées : A, B, C (conditions de sélection et disponibilité)
Sortie : Z (distribution)
Optimisation via Karnaugh pour obtenir une équation minimale

Composants Utilisés
--------------------

- Afficheur 7 segments : [Lien composant](https://example.com/7segment)
- Bascule JK : [Lien composant](https://example.com/jk-flipflop)
- Boutons poussoirs : [Lien composant](https://example.com/button)
- LEDs d’état : [Lien composant](https://example.com/led)
- Alimentation 5V : [Lien composant](https://example.com/5v-power)

(⚠️ Remplacer les liens par ceux réellement utilisés dans votre projet)

Prérequis Matériel et Logiciel
------------------------------

- Logiciel de simulation logique (Logisim, Proteus, Tinkercad Circuits…)
- Breadboard + composants réels (si montage physique)
- Compréhension des circuits combinatoires et séquentiels

Organisation du Projet
----------------------

- Étape 1 : Conception logique (papier)
- Étape 2 : Création du tableau de vérité
- Étape 3 : Karnaugh et équations
- Étape 4 : Schéma sur logiciel ou montage réel
- Étape 5 : Tests + démonstration

Auteur
------

Projet réalisé en groupe dans le cadre de la Licence Informatique – Systèmes numériques – 2025.
