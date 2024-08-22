# **Cas pratique Ventes** <a href="../"><img align="right" src="../assets/powerBi.png" alt="Power BI" height="64px"></a>
## Importer les données
1. Importer les données :
    * L’importatin des tableau est plus qualitative que celle des onglets
    * ’`Charger`’ envoi les données à Power BI est créer le rapport (les données peuvent êtres nettoyées ultérieurement) ;
    * Le bouton ’`Transformer les données`’ permet de les netttoyer avant de les importer via l’éditeur Power Query pour automatiser la transformation des données ;
2. Renommage :
    * Les tableaux sont des requêtes ;
    * Renommer les requêtes de la façon la plus conviviale ;
    * Renommer les en-têtes de la façon la plus claire (les colonnes cummunes aux requêtes ont le même nom) ;
3. Vérifier les types de données :
    * Surveiller la jauge :
        * Le vert si les données sont conformes ;
        * Le rouge, chercher une erreur et cliquer sur la cellule pour identifier l’erreur (ça peut être une commande annulée) ;
        * Le gris signifie qu’il y a des cellules vides ;
    * Supprimmer les erreurs ;
    * Supprimer les éléments vide en positionnant le curseur sur la jauge ;
    * Pour la rabais, remplacer les erreurs par 0.
4. Transformer les données et fusionner les colonnes prénom et nom en colonne “Nom complet” :
    * Fusionner via <bd>ctrl</kbd>, le séparateur est un espace, la nommer “Nom complet”, puis `OK`.
5. Réaliser un profilage statistique :
    * Dans le ruban Affichage, activer le ‘Profil de colonne’, si ce n’est pas le cas ;
    * Il y a 810 lignes, 793 clients et 790 apparaissent une seule fois, _il y a des doublons_ ;
    * La ditributions des valeurs montre 3 clients apparaisssants plusieurs fois (e.g. L’un 7 fois) ;
    * Via le clique droit sur ‘Numéro de Client supprimer les doublons’ ; le nombre de clients et maintenant égale au nombre de valeur unique.
6. charger les données pour l’analyse :
    * Dans le ruban ‘Accueil’, ‘Fermer et appliquer’ ;
    * Toutes les requêtes sont dans l’onglet ‘Données’ ;
    * Aller dans le ‘Vue de modèle’ ;
        * Supprimer les relations ;
        * Retourner dans rapport
## **Visualiser les données**
1. Ajouter des indicateurs aux rapport via la méthode implicite :
    * La quantité ;
    * Le nombre de commande ;
    * Le nombre de clients.
2. Comprendre les relations (croiser les infos de plusieurs tables) :
    * Créer la relation entre les tables “Commande” et “Client” ;
    * Ajouter le segment puis la quantité ;
    * Choisir un graphique en anneaux ;
    * Centre la légende en bas.
3. Concevoir un graphique incluant des données temporelles :
    * Séléctionner la date de commeande et la quantité ;
    * Faire un graphique en courbe et séléctionner le niveau mensuel.
4. Options basiques des paramètres visuels :
    * Dans le menu “Mettre en forme le vusuel”, “Général”, “Propriétés” : donner la même taille à ‘Quantité’, ‘Commande’ et ‘client’ et dans le ruban format : les aligner en haut et les distribuer horizontalement ;
    * Aligner les graphiques avec les cartes ;
    * Changer et centrer les titres des graphiques ;
    * Concernant l’évolution des quantité :
        * Supprimer les titres sur les abscisses (x) et les ordonnées (y) ;
        * Pour facilité la lecture, activer les marqueurs et les étiquettes de données.
5. Insérer un segment :
       * Catégorie de produit ;
       * Afficher par vignette et supprimer l’en-tête ;
       * Créer la relation entre les commandes et produits.
6. Peaufiner la mise en forme d’un rapport :
    * Mettre un titre ;
    * changer l’arrière-plan du canvas.