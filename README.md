je vais essayer de donner quelques details sur le developpement d'un api avec vuejs
comment mettre en place l'environnement de travail vuejs
1-on lance la commande npm init vue@latest   qui permet la creation du projet et le fichier packages.js
2-nmp install l'installation des packages 
3-axios qui nous permet de lancer des requetes http avec des api
4-npm run dev pour lancer le serveur 
2ere partie 
la creation d'un api en utilisant json server 
1-on va aussi lance la commande  npm install -g json-server
2-Créer un db.jsonfichier avec quelques données

{
   "messages" : [
    { "id" : 1 , "title" : " json-server " , "author" : " typicode " }
  ],
  "commentaires" : [
    { "id" : 1 , "body" : " un commentaire " , "postId" : 1 }
  ],
  "profil" : { "nom" : " code type " }
3-Démarrer le serveur JSON

json-server --watch db.json
voila en resume ce qu'il faut pour faire pour la munipulation des apis avec vuejs
