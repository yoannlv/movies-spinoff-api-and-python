# movies-spinoff-api-python

## Contexte du projet

Le Client Floupics a un souci maintenant qu'il a différents formats de données (JSON, PostGreSQL et autres) en entrées d'applications.

Votre Product Owner vient vous demander un service pour ne pas démultiplier les formats et pouvoir centraliser dans une seule BDD SQL toutes les Data nécessaires.

Ainsi, votre mission, si toutefois vous l'acceptez, est de :

analyser les docs et tutos en ressources fournis par votre Lead Dev Data.
proposer une analyse fonctionnelle métier du départ à l'arrivée de la demande sous forme de schéma UML.
à partir de ces nouvelles données récupérables par API [http://www.omdbapi.com/] et avec l'aide de l'outil open source Postman,
vous allez créer une nouvelle base de données sous PostGreSQL avec une ou plusieurs Tables selon les Clefs récupérées et votre force de propositions à partir de scripts Python.
enfin vous allez afficher très basiquement avec Python et le langage de template JINJA2 les données de la BDD PostGreSQL sur une seule page qui sera dénommée « index.html »

## Contenu du repository

 - dossier _templates_ contenant la structure HTML du tableau
 - dossier _html_ contenant le rendu final
 - fichier README
 - notebook _movies-spinoff-api-python.ipynb_ comprenant les étapes de connexion à la base de données, de création de la table, d'insertion des données puis de lecture des données sur le fichier _index.html_