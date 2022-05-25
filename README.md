# SQL "Location de film"
-----------Ce projet consiste à créer une base de donnée pour le stockage  des des renseignements sur les clients et les films------------

# création de table
Nous avons suivi la même procéduire pour créer toutes les tables à savoir : infocategories, infocliens, infofilm, infoLocation(table intermédiare) et infopayements. exemple :
--------Create Databases infoclients (primary key(codeclient(INT)), nom VACHAR(30), prenoms VACHAR(45), email VACHAR (50)) values (abalo, sylvie, sylvieabalo48@gmail.com)------

# Ajouter les données 
-------INSERT INTO client.infoclients (Codeclient, nom, prénoms, email) values (abalo, sylvie, sylvieabalo48@gmail.com).---------

# Modifier les données
------ALTER TABLE client.infoclients;-------------

# Sélectionner les données
------------SELECT * FROM  clients.infoclients;--------
