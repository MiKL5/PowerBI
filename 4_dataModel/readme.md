# **Le `data model` 📈**  <a href="../"><img align="right" src="../assets/powerPivot.png" alt="Power Pivot" height="64px"></a>

Le `data model` est une zone d'entrée de `Power Pivot`.  
Il est composé de trois onglets à gauches. Le premier pour la visualisation (zone `Rapport`).  
Le deuxième, permet de visualiser les données (zone `Données`).  
Le troisième, pour voir les relatons potentielles entre les tables (zone `Modèle`).  

___
## **Qu'est-ce que les relations et à quoi ça sert ?**

Ça ressemble aux jointures, mais les tables ne sont pas modifiées si l'une d'elles est modifiée.  
Tant qu'on ne le demande pas, il n'y a pas de jointure pour rassembler les deux. La jointure n'est utilisée que lors du croisement dans la zone de rapport.  
Donc pas de calcul inutile, pas de duplication des données.  

Power BI peut détecter les relations entre les tables. Le sens de la jointure est indiqué, ainsi que des chiffres qui déterminent le type de cardinalité.  

Les cardinalités indiquent le sens des filtres.

## **Gestion du data model**

* Créer une relation
* Relation `1 à 1` :  
  >Une seule clé par tableau de liaison, donc la liaison ce fait avec une valeur unique dans les deux tableaux. Il n'y a pas de retraitement à faire sur les données du fait que les valeurs sont uniques pour chaque colonne.
* Relation plusieurs à 1 `* à 1` :  
  >Le 1er tableau à des clés dupliquées. Utile s'il y a plusieurs festivals par région par ex.
* Relation `1 à *` :  
  >Effet similaire, cette relation permet l'agrégation de données, car ça vient d'une valeur unique par festivals pour avoir la somme des participants.
* Relation `* à *` :  
  >De chaque côté de la clé de réconciliation des 2 tables, il y a des valeurs dupliquées. Utile avec les tranches d'âges par ex. Il peut donc y avoir des étapes intermédiaires de réagrégation (par ex : pour la somme des habitants par département).
* Les filtres directionnels
* Désactiver une relation
* Utiliser le filtre de sécurité bidirectionnel :
  > Ça permet de rôles et donner l'accès des informations du fichier selon les besoins.
* Intégrité relationnelle supposée
  > C'est disponible uniquement avec Direct Query, ici. Ceci veut dire qu'il y a une clé spécifique et passe en mode jointure interne.
* Gérer les relations
* Théorie sur le modèle en étoiles
* Modèle en étoile dans le pratique

[TP](tp)