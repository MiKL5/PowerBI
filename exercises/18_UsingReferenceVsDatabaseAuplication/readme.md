# **Utiliser la référence vs la duplication d’une base de données**
Une table dupliquée n’a pas de relation avec la table d’origine.  
La base référente sera quant à elle impactée par _toutes_ les modifications à la table originale.  
Les bases référentes n’ont toujours que l’étape sources, nonobstant, il est important de les identifier dans le nom.

La duplications sert par exemple à étudier particulièrement une colonne. Cela permet de modifier sans dégrader la base d’origine.