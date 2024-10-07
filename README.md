# Conception Logicielle

Teams

UML - meurize ( conception base de donnée surtout) - Agilité

## Ressources

YT - Delphine Longuet
Looping-MCD ( uniquement windows ) : - meurize => définition entité => génere multitude de diagramme ( MLD (modele logique), code sql, )

## Intro

UML ( unified Model Language ) :

- standard conception ( pas seulement dev projet)
- echange technique avec non
- initié faciliter
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
