# Simulation Numerique

Ce dépôt contient du code Python pour les algorithmes CUR et randomized CUR de compression d'images.

Le code est implémenté dans un notebook Jupyter et peut être utilisé pour compresser les images suivantes (qui sont dans ce dépôt également) :

- Toulouse.png
- Taipei.jpg
- Sydney_Opera_House.jpg
- Tokyo_Rainbow_Bridge.jpg
- Hamburg_Elbphilarmonie.jpg

Le code inclut également une fonction pour la factorisation de matrices non négatives (NMF), qui peut être utilisée pour comparer les performances des algorithmes CUR et randomized CUR.

Pour utiliser le code, installez d'abord les packages Python nécessaires :

    pip install numpy scipy matplotlib

Ouvrez ensuite le notebook Jupyter et exécutez les cellules.

Les résultats de la compression sont affichés dans le notebook.

Le code fonctionne de la manière suivante :

1. Il charge les images à partir des fichiers.
2. Il utilise la fonction cur ou randomized_cur pour compresser les images.
3. Il utilise la fonction nmf pour compresser les images avec NMF.
4. Il affiche les images compressées.


Le code utilise les paramètres suivants :

1. erank : le rang cible de la compression.
2. epsilon : un seuil relatif pour la précision de la compression.
3. blocking : le nombre de blocs utilisés pour la détermination du rang avec l'algorithme CUR.
4. iteration_max : le nombre maximal d'itérations pour l'algorithme NMF.

Vous pouvez modifier ces paramètres pour obtenir des résultats différents.
