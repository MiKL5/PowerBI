La fonction SUM s’utilise pour un calcul simple.
```DAX
CA TOTAL = SUM(Base de 2020[Chiffre d'affaires] )
```
Contrairement à la fonction SUMX, dont le calcul est fait ligne à ligne
```DAX
Profit / produit = SUMX(Base de 2020 , Base de 2020[Chiffre d'affaires] - Base 2020[Coût total] )
```
Car le chiffre d’affaire diffère par villes et produits.