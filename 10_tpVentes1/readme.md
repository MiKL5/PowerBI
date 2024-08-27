# Analyse des ventes <a href="../"><img align="right" src="../assets/powerBi.png" alt="Power BI" height="64px"></a>
## **Graphique de base**
1. Créer la carte des quantités ;
2. Créer le graphique à barre empilées des ventes par catégories ;
3. Filtrer les pays par segment.
##  **Les fondamentaux de l’analyse de données avec DAX**
1. Créer une mesure implicite<!-- (automatiquement gérées par Power BI) --> ;
2. Créer une meusure explicite en DAX <!--(avantages : ne permet pas la changemnt d'agrégtion par errer, réutilisable à volonté dans une carte, une formule, ...) -->;
3. Créer une mesure DAX automatique<!-- (nouvelle mesure rapide, valeur de base: quantités vendues et le filtre : pays et éventuellement une valeur)--> ;
4. Référencer des mesures existantes ;
5. Formater correctement des mesures DAX <!--(doucle cliquer sur la mesure et dans le ruban ‘Outils de mesure’, Choisir le format pourcentage)--> ;
6. Organiser les mesures DAX correcttement<!-- (dans le ruban ‘Accueil’, ‘Entrér des données’, en bas nommé “Mesures”. Puis à gauche dans ‘Vue de modèle’ et dans l’onglet ‘Données’ à droite déplacer les mesures)--> ;
## **Créer des indicateurs avancés avec DAX**
1. Ajouter la métrique du Chiffre d’Affaires<!-- (sumx() fait la somme par ligne)--> ;
2. Ajouter celle du coût total ;
3. Ajouter la mesure proflt ;
4. Ignorer le segment ;
5. Concevoir le ratio pourcentage<!-- (créer la mesure et séléctionner % avant d'appuyer sur entrée)-->.
<!-- ## **Mener des analyses temporelles** -->
<!-- 1. Le fonctionnement des dates ; -->
<!-- 2. Les différents niveaux de hiérarchie ; -->
<!-- 3. Créer une table calendrier personnalisée ; -->
<!-- 4. Calculer un cumul annuel ; -->
<!-- 5. Aficher une variation par année. -->