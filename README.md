# Laboratoire de recherche - Création d'une base de données.

En équipe de trois, nous avons, dans un premier temps, analysé et conçu une base de données à l'aide d'un fichier CSV. Nous avons ensuite implémenté et exploité cette base de données à l'aide de requêtes et de fonctions SQL. Nous avons utilisé [PostgreSQL](https://www.postgresql.org/) comme système de gestion de base de données.

- [Explications par le laboratoire de recherche](explications.pdf)
- [CSV fourni pour effectuer le projet](personnelLabo.csv)
- [Modèle Conceptuel de Données](analyse-conception/mld.PNG)
- [Script de création du schéma ``labo``](implementation-exploitation/creationTables.sql)
- [Script d'insertion de données](implementation-exploitation/insertionDonnes.sql)
- [Script des requêtes SQL](implementation-exploitation/requetes.sql)
- [Script des fonctions SQL](implementation-exploitation/fonctions.sql)

## 1 - Analyse et conception de la base de données.

Dans cette partie, nous avons fait le dictionnaire des données en présentant la liste des propriétés nécessaires pour le fonctionnement du système d'information. Pour chaque propriété, nous avons indiqué son nom, son code, son type, sa taille et les éventuelles contraintes la concernant.

Nous avons ensuite déterminé, à l'aide du dictionnaire de données, la liste des dépendances fonctionnelles. Après cela, nous sommes passés à la conception du Modèle Conceptuel de Données et au [Modèle Logique de Données](analyse-conception/mld.PNG) à l'aide de Looping.

## 2 - Implémentation et exploitation de la base de données.

Dans cette partie, nous avons créé le [script permettant la création des tables](implementation-exploitation/creationTables.sql), [l'insersion des données](implementation-exploitation/insertionDonnes.sql) dans les tables et l'interrogation de la base par l'intermédiaire de [requêtes](implementation-exploitation/requetes.sql) et de [fonctions SQL](implementation-exploitation/fonctions.sql).

Pour l'insertion des données, nous avons dû créer des scripts python pour extraire les données du [CSV fourni](personnelLabo.csv) pour le diviser en d'autres CSV, correspndant au mieux à nos tables.