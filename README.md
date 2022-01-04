# KayakProject

Bloc n°1 : Construction et alimentation d'une infrastructure de gestion de données.

Délivrables :
- Un fichier .csv dans un bucket S3 contenant des informations à propos de la météo et des hotels pour chaque ville de France (liste donnée au préalable)
- Une base SQL propre où l'on peut extraire les données contenues dans le bucket S3
- Deux cartes avec un Top 5 des destinations et un Top 20 des hotels dans chaque ville

Fichiers :
SCRAPING_TEMPS : notebook extraction des informations météo sur la liste de villes donnée
SCRAPING_BOOKING : notebook scraping des données des hôtels sur le site booking.com pour les 5 villes identifiées précedemment
PROJET_KAYAK : notebook contenant les maps et les données météos + hôtels en un fichier 
scrap_hotels.csv : fichier csv généré suite au scraping des données sur booking.com
kayak_cities_weather_noindex.csv : fichier csv généré suite aux requêtes API pour obtenir les données météo
hotels_meteo_complete.csv : fichier csv avec les données météo et hôtels 
