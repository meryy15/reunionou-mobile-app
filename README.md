# Reunionou
Ce projet permet d'organiser des événements depuis son smartphone ou son ordinateur à travers une API afin de gérer toutes les informations. (lieu, membres, météo, discussion, ...)
Ce dépôt contient l'application mobile développée en Flutter.

## Planning :
- Date de début : **21 Mars 2022**
- Date de fin : **30 Mars 2022**

## Membre de group :
- Youssef Bahi (youssef.bahi1@etu.univ-lorraine.fr)
- Malek Ben Khalifa (malek.ben-khalifa3@etu.univ-lorraine.fr)
- Sebastien Klaus (sebastien.klaus2@etu.univ-lorraine.fr)
- Maxime Piscalgia (maxime.piscaglia1@etu.univ-lorraine.fr)
- Armand Perignon (armand.perignon3@etu.univ-lorraine.fr)

## Version Flutter :
* Flutter 2.10.3
* Dart 2.16.1
* DevTools 2.9.2

## Lien utiles :
- Version web de l'application (Admin): https://reunionou-admin.netlify.app/
- Version web de l'application (client): https://reunionou.netlify.app/
- Documentation : https://reunionou-doc.netlify.app/
- Tableau de bord (Trello) : https://trello.com/b/fEIl2eXh/tableau-de-bord

## Code source :
- Version web de l'application (Admin): https://github.com/sebastienklaus/reunionou-admin-webapp
- Version web de l'application (client): https://github.com/you97ssef/reunionou-web-app
- Version mobile : https://github.com/malekbk98/reunionou-mobile-app
- Back-office : https://github.com/sebastienklaus/reunionou/tree/develop

## Installation :
** Note : avoir une version de Flutter compatible
``` reunionou> flutter run --no-sound-null-safety```

## En cas d'erreur lors de l'instatllation:
1) ``` reunionou> flutter clean ```
2) ``` reunionou> flutter pub get ```
3) ``` reunionou> flutter run --no-sound-null-safety ```

## Génération du fichier. Apk :
``` reunionou> flutter build apk --split-per-abi --no-sound-null-safety ```

## Fonctionnalités :
- S'authentifier en tant qu'utilisateur
- Rejoindre un événement en tant qu'invité
- Ajouter/modifier un événement (** utilisateur authentifié uniquement**)
- Ajouter des membres à un événement
- Localiser l'événement depuis un point sur la map/saisir l'adresse- Partager un événement
- Possibilité de rejoindre/decliné un événement
- Voir la liste des participants
- Ajouter des commentaires
- Voir les commentaires d'autres participants
- Voir la géolocalisation d'un événement
- Voir la météo selon l'adresse de l'événement
- Obtenir l'itinéraire vers l'adresse de l'événement
- Modifier son profil

## Technologies :
- Backoffice : Vue.js
- Web app : Vue.js
- Mobile app : Flutter
- Backend : Slim
- Database : Adminer + Sql