# 🎥 **TP Cinéma** 🎥 <a href="../"><img align="right" src="../assets/powerBi.png" alt="Power BI" height="64px"></a>

<div align="center">

## **Entrées par jour**

</div>

* Importez la table des entrées par jour
* Des lignes vides apparaissent en bas de tableau, supprimez-les
* Des colonnes vides apparaissent également en fin de tableau, conservez uniquement celles qui contiennent des données 
* On voit que le nombre de décimales n’est pas le même selon les lignes. Unifiez cela en arrondissant toutes les valeurs des jours de la semaine à 2 décimales après la virgule
* Dépivoter le tableau afin de ne plus avoir que 3 colonnes : l’année, le jour de la semaine, les valeurs de répartitions
* Les valeurs sont en réalité des pourcentages. Divisez la colonne des valeurs par 100, puis passez la colonne au format pourcentage

<div align="center">

## **Séances par mois et entrées par Origine**

</div>

* À partir des modifications réalisées sur la table précédente, déduisez l’ensemble des retraitements à appliquer sur ces tables

<div align="center">

## **Fréquentation cinéma global**

</div>

* Supprimez les colonnes vides en fin de tableau
* Changez le format des colonnes en fonction de ce qui a été proposé par power query
* Il y a un problème sur certaines colonnes, qui contiennent des « -« , à la place d’une valeur null. Remplacez cette valeur afin de pouvoir convertir la colonne dans un format numérique

<div align="center">

## **Retraitement de données**

</div>

* Dans la table « séance par mois » créez une nouvelle colonne permettant d’avoir le mois en format nombre
* Dans la table « séance par mois » créez une nouvelle colonne permettant d’obtenir une date avec la combinaison de l’année et du mois (le jour sera systématiquement le premier jour du mois)
* Dans la table « Entrée par origine », le terme « films » apparait systématiquement dans la colonne « origine des films » ce qui n’est pas pertinent. Supprimez les mentions « films » dans les valeurs de la colonne. Selon la méthode utilisée, il est possible que vous vous retrouviez avec des espaces inutiles dans les valeurs, trouvez une solution pour corriger ça.
