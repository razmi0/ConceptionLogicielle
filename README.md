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

### Meurise

- dans phase de conception
- shéma normalisé facilitant la communication

- concentration sur le systeme d'information et base de données
- traduit modele en base de données
- franco-français
- 3 niveaux de conception :
  - conceptuel ( MCD ) => uniquement champs visible ( pas de table de relation et clé étrangères) => clé primaire = identifiant
  - logique ( MLD ) => transforme le MCD => cardinalité devient clé étrangère. Si deux 0,n ou 1,n => table de relation car c'est un many to many avec un clé primaire composite ( id1, id2 )
  - physique ( MPD ) => rajoute les typage SQL, le typages => peut posséder les valeurs par défaut
- trés lié à documentation

⚠️ Attention aux many to many qui sont les plus complexe est font spawn des tables de relation. L'id composite prévient de duplication d'article( id1 + id2 )

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
