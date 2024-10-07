# Conception Logicielle

Teams

UML - Merise ( conception base de donnée surtout) - Agilité

## Ressources

YT - Delphine Longuet
Looping-MCD ( uniquement windows ) : - Merise => définition entité => génere multitude de diagramme ( MLD (modele logique), code sql, )
EXCALIDRAW : <https://excalidraw.com/#json=8HVsClc7L2kZhI-Tf8W9r,jWZPO14ej159mgWawZtbgg>

## Intro

UML ( Unified Modeling Language ) :

- standard conception ( pas seulement dev projet)
- echange technique avec non initié facilité
- multiplicité acteur dans conception
- facilite migration stack technique

concentration besoin puis technique
different types de diagramme
ici essentiellemnt fonctionelle

point de départ projet : definir besoin

---

Gestion de projet : avant agilité => cycle en V ( un sprint de 6 mois, + de 90% d'echec)
Agilité : centralisation sur fonctionelle, product owner valide les sprints, si fin du sprint répond aux besoins définis => validation

### UML

Etapes :

- Phase d'analyse :
  - production du diagramme des cas d'utilisations :
    - shéma avec acteurs externe
    - cadre = application
    - cercle = fonctionallité
- Phase conception :
  - production diagramme d'activité :
    - uniquement fonctionelle
    - shéma retranscrisant la logique métier ( composant métiers, uses cases )
    - conception ( affichage produits, quels acteur ?, toute la dynamique autour des produits )
    - donne repére aux dev autant front
    - fin de conception
      - production diagramme de séquence
        - evenement acteur et sequantialisation evenement et logique depuis l'interface
        - appel a des routes et activation d'instances d'objet, entité, model, fragment ( test ) jusqu'a verification donnée aprés appel base de donnée et retour à l'interface.

### Camp de vacances

cas utilisation :

- client (voir les offres)
- client connecté (voir les offres, gerer ses réservations, gerer ses avis, gerer ses services )
- personnel d'accueil (gerer les reservations, gerer les avis, gerer les services)
- personnel commercial
- administrateur(gérer l'ensemble)

definition besoin :

-
- choisir l'intervalle de reservation
-

définition features

- date d'arrivée plus ou moins 3 jours
- filtrage des offres

filtres :

- type (tentes, camping-car / caravane, et des mobilhomesChalets, tipy )
- prix (croissant , décroissant)
- taille (superficie, Q lits)
- ranking (possibilité de mettre des offres en avant)
- options ( clim, wifi, radiateur)
- "theme"

Services et activité sur place

- piscine
- salle de sport
- piscine jet massant
- aire de jeux
- ménage
