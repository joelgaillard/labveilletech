+++
title = "8 Design Patterns EVERY Developer Should Know"
date = "2023-02-06"
+++

[![Video](https://img.youtube.com/vi/tAuRQs_d9F8/maxresdefault.jpg)](https://www.youtube.com/watch?v=tAuRQs_d9F8)

Cette vidéo explique avec humour huit modèles de design patterns essentiels que tout développeur devrait connaître, tirés du livre « Gang of Four » de 1994. 

Le présentateur utilise le python pour illustrer ses propos, mais ces designs patterns sont évidemment utilisables sur les autres langages.

Ces modèles sont classés en trois catégories : les modèles de création, les modèles structurels et les modèles comportementaux. 

## Les designs patterns abordés

### Modèles de création

- Factory : Simplifie la création d'objets en déléguant leur instanciation à une méthode ou une classe spécifique, masquant ainsi la logique complexe.

- Builder : Permet de construire des objets complexes étape par étape, en séparant la logique de construction de la représentation finale.

- Singleton : Garantit qu'une classe n'a qu'une seule instance globale accessible, en centralisant son contrôle via une méthode statique.

### Modèles comportementaux
- Observer : Met en place un système où un objet (le sujet) informe automatiquement ses abonnés (observers) des changements d'état, ou sert de base pour un modèle Pub/Sub en découplant émetteurs et abonnés.

- Iterator : Fournit un moyen d'accéder aux éléments d'une collection séquentiellement sans exposer sa structure interne.

- Strategy : Définit une famille d'algorithmes interchangeables dynamiquement, permettant de choisir le comportement souhaité au moment de l'exécution.

### Modèles structurels
- Adapter : Convertit l'interface d'une classe existante en une autre attendue, permettant une compatibilité entre des composants incompatibles.
- Facade : Simplifie l'accès à un système complexe en fournissant une interface unique et simplifiée pour interagir avec ses sous-systèmes.

La vidéo illustre ces designs patterns avec des exemples pratiques, en montrant leurs cas d'utilisation et leurs avantages dans la programmation tout en faisant des parrallèles avec la vie de tous les jours.

## Pertinence pour le thème du développement web

Ces modèles de design patterns sont particulièrement pertinents pour le développement web, car ils permettent de structurer et d'optimiser le code face à des problèmes récurrents. 

Les modèles de création (comme Factory, Builder et Singleton) aident à gérer l’instanciation des objets complexes, essentielle pour les API ou les services backend. 

Les modèles comportementaux (Observer, Iterator, Strategy) facilitent l’interaction entre les composants, comme la gestion des événements dans JavaScript ou les flux de données réactifs dans les frameworks modernes. 

Les modèles structurels (Adapter, Facade) simplifient l’intégration de systèmes hétérogènes et favorisent une conception modulaire, souvent nécessaire pour l’interopérabilité des services et des bibliothèques dans des applications web complexes.

## Mon rapport à cet article

Lors de ma première année d'ingénierie des médias, nous avions survolé le thème des designs patterns (en passant plus de temps sur le singleton), sans entrer dans les détails.

Lors de mon travail de bachelor qui va commencer en avril 2025, je vais être amené à travailler sur le développement de certaines fonctionnalités d'une plateforme web (et faire de la rétroconception) en utilisant un framework PHP custom interne à une entreprise.

La personne chargée du développement de la plateforme m'a déjà mentionné l'utilisation de design patterns en citant notamment le builder et le singleton. 

Cette vidéo et ce résumé seront donc utiles pour revisiter les design patterns et mieux comprendre le code existant dans le framework.


**Source :** https://www.youtube.com/watch?v=tAuRQs_d9F8 

**Image d'illustration :** *Miniature de la vidéo YouTube*






