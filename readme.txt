Ce projet de développement d'application mobile a été réalisé par :
WILLENBUCHER Gurvan et
VALLEE Mathieu
en L3 informatique.


Il s'agit d'une liste de TodoLists avec des requêtes GraphQL permettant de récupérer les données.
Veuillez mettre l'adresse que vous utilisez sur la ligne 1 du fichier 'todoAPI.js' (par défaut c'est localhost sur le port 4000).


Pour lancer ce projet, il faut installer les 2 modules ci-dessous :

expo init todo
cd todo
npm install #--no-bin-links


npm i --save @react-navigation/bottom-tabs @react-navigation/native

npm install react-native-progress --save



Pour utiliser la base de donnée GraphQL, il vous faut une VM ou alors Neo4J sur Windows.
- installez Neo4J, par exemple la version Desktop (avec interface graphique)
- créez un projet puis une base de données dans ce projet, en précisant le mot de passe rootroot
- dans les plug-ins, activez APOC, qui permet de gérer les droits d'accès



Pour lancer, il faut ainsi exécuter les commandes suivantes dans 2 terminaux différents :

Dans la racine : npm start

Dans le dossier de la base de données : node index.js