# **Le `data model`**

Le `data model` est une zone d'entrée de `Power Pivot`.  
Il est composé de trois onglets à gauches. Le premier pour la visualisation (zone `Rapport`).  
Le deuxième, permet de visualiser les données (zone `Données`).  
Le troisième, pour voir les relatons potentielles entre les tables (zone `Modèle`).  

___
## **Qu'est-ce que les relations et à quoi ça sert ?**

ça ressemble aux jointures, mais les tables ne sont pas modifiées si l'une d'elles est modifiée.  
Tant qu'on ne le demande pas, il n'y a pas de jointure pour rassembler les deux. La jointure n'est utilisée que lors du croisement dans la zone de rapport.  
Donc pas de calcul inutile, pas de duplication des données.  

Power BI peut détecter les relations entre les tables. Le sens de la jointure est indiqué, ainsi que des chiffres qui déterminent le type de cardinalité.