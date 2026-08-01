# Architecture --- Project Hub v0

## Modules

-   Tableau de bord
-   Gestion des projets
-   Import / glisser-déposer
-   Classement des fichiers
-   Journal des actions
-   Synchronisation GitHub
-   Paramètres

## Arborescence cible

``` text
Project Hub
├── Tableau de bord
├── Projets
├── Documents
├── Synchronisation GitHub
├── Journal
└── Paramètres
```

## Sécurité

Les opérations destructives devront demander une confirmation. Les
fichiers originaux doivent être préservés lors des imports tant que
l'utilisateur n'a pas validé leur déplacement ou suppression.
