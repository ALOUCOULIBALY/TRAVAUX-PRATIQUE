# TRAVAUX-PRATIQUE 2 : Intégration des données vectorielles et matricielles
****

Les étapes du TP :
****
![image](https://github.com/ALOUCOULIBALY/TRAVAUX-PRATIQUE/assets/158978951/884468a3-56da-4311-b3bf-de330e5b1bea)

****
1- Importation des données dans FME
****
2- Réprojection en 3857
****
3- Analyse statistique 
****
4- Jointure des entités
****
5- Nettoyage des données
****
6- Extraction des méta-données du raster
****
7- Ré-échantillonnage du raster
****
10- Conversion du raster en tuile Vectorielle
****
11- Création ligne de contour 
****
12- Lissage des géométries 
****
13- Création de polygones
****
14- Filtrage de nuage de point
****
15- Combinaison en un seul nuage de point
****
16- Création de MNS
****
17- Visualisation dans différents formats
****
# IMPORTATION DES DONNÉES :
****
Donnée vectorielle quantitative :

https://donnees.montreal.ca/dataset/2faa580d-d127-4a30-a79a-1ebf9d255f9b/resource/88bb6a18-54fa-4789-82e8-14888a933a4a/download/sondage-echo-donnees-2020.csv
****
Donnée vectorielle qualitative : 

https://donnees.montreal.ca/dataset/1c1a9b72-efaa-4484-9b19-2ab9a5561cfa/resource/5ca26973-7df6-472e-9bc0-5213a2445082/download/indice-equite-milieux-vie.csv
****
Donnée vectorielle avec 3D : 
****
Nuage de points : 

http://depot.ville.montreal.qc.ca/geomatique/lidar_aerien/2015/299-5040_2015.laz

http://depot.ville.montreal.qc.ca/geomatique/lidar_aerien/2015/298-5040_2015.laz
****
Image aérienne :
****

# REPROJECTION DES DONNÉES :
****
Toutes les données sont reprojetées en 3857 avec Reprojector dans FME
****
# ANALYSE STATISTIQUE :
****
Analyse différenciée selon le sexe et le statut d'immmigration de la donnée quantitative
****
# JOINTURE DES ENTITES :
****
Jointure des entités de la donnée quantitative
****
# NETTOYAGE DES DONNÉES : 
****
Rétirer certaines variables de la donnée qualitative
****
# EXTRACTION DES META-DONNEES DU RASTER :
****
Rastérisation de l'image aérienne
****
# RE-ECHANTILLONAGE DU RASTER :
****
Division du nombre de nuage de points par 2 
****
# CREATION DE SERIES DE PYRAMIDES :
****
Ajout de deux niveaux de raster
****
# CREATION DE CODE SQL :
****
Pour afficher le niveau 1
****
# CONVERSION DES DONNEES EN TUILE :
****
Création de tuile vectorielle
****
# CREATION DE LIGNE DE CONTOUR :
****
Création de ligne de contour pour la donnée vectorielle avec 3D
****
# LISSAGE DE GEOMETRIES :
****
Lissage de géométrie avec un seuil de tolérance de 10 
****
# CREATION DE POLYGONES :
****
Création de polygones pour la donnée vectorielle avec 3D
****
# FILTRAGE DE NUAGE DE POINTS :
****
Filtrage pour les deux nuages de points avec un interval de 100
****
# COMBINAISON EN UN SEUL NUAGE DE POINT :
****
Combinaison des deux nuages de points en un seul
****
# Création de MNS:
****
Création de modèle numérique de terrain en se basant sur un algorithme de triangulation paramétrable.
****
# VISUALISATION DANS DIFFÉRENTS FORMATS :
****
Visualistion de la donnée vectorielle quantitative en PostGis

Visualisation de la donnée vectorielle qualitative en PostGis

Visualisation de la donnée vectorielle avec 3D en PostGis : ![image](https://github.com/ALOUCOULIBALY/TRAVAUX-PRATIQUE/assets/158978951/31ab71c3-8d6e-422d-b868-d38722ec8d81)


Visualisation des nuages de points en PostGis : ![image](https://github.com/ALOUCOULIBALY/TRAVAUX-PRATIQUE/assets/158978951/1363887d-ea0a-43c8-9394-40ee5621c90c)


Visualisation de l'image aérienne en PostGis :  ![image](https://github.com/ALOUCOULIBALY/TRAVAUX-PRATIQUE/assets/158978951/f450d7b2-5f03-4d59-bd01-bbfb688fd0c3)

****
