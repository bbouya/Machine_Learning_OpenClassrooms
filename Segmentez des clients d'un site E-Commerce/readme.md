# Segmentez des clients d'un site E-COMMERCE

#### OPenclassroom - Ingenieur Machine learning

##### Problematique : 
Fournissez au equipes d'e-commerce de olist une segmatation des clients qu'elles pourront utiliser au quotidien ppour leurs campagnes de communication.

###### 9 datasets componants une partie de la base de donnees client du site internet Olist. les base de donnees decrivent l'historique de commandes et d'achats avec le site internet des clients.

### Data set initial :
    - 9 bases de données relieés par des clés uniques.
    - plus de 96 000 client pour presque 110 000 articles passes sous commmande.
    - Feature dont: 
            * Les dates (et prix) de commandes, de livraison, status de livraison.
            * Des info geographiques sur les clients ainsi que leurs evaluation de la commande et si ils ont laisse des commantaires, leurs paiments et moyens de payments sont aussi decris.
            * La categories des produit achetés et de leurs vendeurs ainsi qu'unr description physiques de produits.
    
    Pistes: 
        * Creation de nouvelles variables.
        * Clustering de la donnes une fois compresse a basse dimension.
        * Segmentation RFM.

## Merge 'order' data with 'customers' data:
On verfie que le customer_id est une jointure entre les tables orders & customers: on va donc commencer par faire un merge de ces 2 tables.
        * Nombre de lignes dans data orders : 99441
        * Nombre de lignes dans customers : 99441
        * Nombre decustomer_iduniques dans customers: 99441
        * Shape de orders : (99441, 8)
        * shape de customers : (99441,5)


