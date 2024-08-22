# **Cas pratique Ventes** <a href="../"><img align="right" src="../assets/powerBi.png" alt="Power BI" height="64px"></a>
## Importer les données
* Importer les données ;
    1. L’importatin des tableau est plus qualitative que celle des onglets
    2. ’`Charger`’ envoi les données à Power BI est créer le rapport (les données peuvent êtres nettoyées ultérieurement) ;
    3. Le bouton ’`Transformer les données`’ permet de les netttoyer avant de les importer via l’éditeur Power Query pour automatiser la transformation des données ;
* Renommage ;
    1. Les tableaux sont des requêtes ;
    2. Renommer les requêtes de la façon la plus conviviale ;
    3. Renommer les entêtes de la façon la plus claire (les colonnes cummunes aux requêtes ont le même nom) ;
* Vérifier les types de données ;
    1. Surveiller la jauge :
        * Le vert si les données sont conformes ;
        * Le rouge, chercher une erreur et cliquer sur la cellule pour identifier l’erreur (ça peut être une commande annulée) ;
        * Le gris signifie qu’il y a des cellules vides ;
    2. Supprimmer les erreurs ;
    3. Supprimer les éléments vide en positionnant le curseur sur la jauge ;
    4. Pour la rabais, remplacer les erreurs par 0.
* Transformer les données et fusionner les colonnes prénom et nom en colonne “Nom complet” ;
    1. Fusionner via <bd>ctrl</kbd>, le séparateur est un espace, la nommer “Nom complet”, puis `OK`.
* Réaliser un profilage statistique ;
    1. Dans le ruban Affichage, activer le ‘Profil de colonne’, si ce n’est pas le cas ;
    2. Il y a 810 lignes, 793 clients et 790 apparaissent une seule fois, _il y a des doublons_ ;
    3. La ditributions des valeurs montre 3 clients apparaisssants plusieurs fois (e.g. L’un 7 fois) ;
    4. Via le clique droit sur ‘Numéro de Client supprimer les doublons’ ; le nombre de clients et maintenant égale au nombre de valeur unique.
* charger les données pour l’analyse.
    1. Dans le ruban ‘Accueil’, ‘Fermer et appliquer’ ;
    2. Toutes les requêtes sont dans l’onglet ‘Données’ ;
    3. Aller dans le ‘Vue de modèle’ ;
        * Supprimer les relations ;
        * Retourner dans rapport
## **Visualiser les données**