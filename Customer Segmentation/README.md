## Introduction :
Ce notebook regroupe le travail de nettoyage de données, 
d'analyse exploratoire et de feauture engeeniring réalisé sur 
les données de consommation électrique des bâtiments de la ville de Seattle.
il etait demande de realiser : 
 - Le nettoyage et l'expoloration des donnees.
 - Construire des variables learning (feature engineering).
 - Entrainer differntes familles de modeles de machine learning
 - Selectionner le /les meilleur modeles et definir les hyperparamtres permettant d'atteindre les meilleures performances
 - Deternminer si la variable ENERGYSTARSCORE, couteuse a calculée, est necessaire pour l'entrainement des modeles
 
 
## Contenu de repository : 
 - Un notebook de nettoyage et l'exploration des données et de construction de variables.
 - Un notebook presentant l'entrainement des modeles,
 - Une presentation de synthése.
 

# Contexte : 
La maketplace brésilienne Olist cherche à réaliser une segmentation de ses clients afin de réaliser de futures actions de communication/marketing.

Afin de la réliaser le site mais à disposition les données des transactions réalisée depuis janvier 2017. Celles-ci sont réparties dans plusieurs fichiers:

olist_customers_dataset.csv : Listing des clients
olist_geolocalisation_dataset.csv: Données de localisation des clients
olist_order_items_dataset.csv: listing des produits commandés
olist_order_payments_dataset.csv: Listing des paiements
olist_order_reviews_dataset.csv: Listing des évaluations clients
olist_orders8dataset.csv: Listing des commandes
olist_sellers_dataset.csv: Listing des vendeurs
olist_product_category_name_translaion.csv
Le site souhaite également qu'un devis de contrat de maintenance de la segmentation soit réalisé.