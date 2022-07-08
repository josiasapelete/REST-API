# REST-API

 Création d'un API REST pour la gestion des statistiques des joueuses de foot de l'équipe nationale du Togo.
 
<img width="960" alt="Capture d’écran 2022-07-08 090956" src="https://user-images.githubusercontent.com/102300897/177937196-d1640203-2aad-4ccf-84ad-0187e1b2d893.png">

Lien vers le site https://peaceful-chamber-91125.herokuapp.com/

AH OUI! c'est ce que donne le visuel c'est parce que c'est juste du back-end il y a pas du front

Les Technologies utilisées:
-Node.js
-Express.js
-JavaScript
-Git 
-Json
-Postman (Pour le Test)

Ressource:
https://rapidapi.com/blog/nodejs-express-rest-api-example/
https://medium.com/@9cv9official/what-are-get-post-put-patch-delete-a-walkthrough-with-javascripts-fetch-api-17be31755d28
https://www.geeksforgeeks.org/basics-of-api-testing-using-postman/

Fonctionnement:
Pour faire un:
-GET:Pour avoir un joueur  https://peaceful-chamber-91125.herokuapp.com/api/v1/stats/id
-POST: pour inserer un joueur https://peaceful-chamber-91125.herokuapp.com/api/v1/stats et insérer les données sous format Json dans le body avec l'option Raw
{
      "id": 1001,
      "name": "Jo",
      "wins": 10,
      "losses": 3,
      "points_scored": 7
  }
  <img width="960" alt="Capture d’écran 2022-07-08 085449" src="https://user-images.githubusercontent.com/102300897/177934555-c7408ac0-ba02-409b-aa66-53387ff87c7e.png">
-PUT : Pour modifier les données d'un joueur    https://peaceful-chamber-91125.herokuapp.com/api/v1/stats/id
-DELETE: Pour effacer un joueur   https://peaceful-chamber-91125.herokuapp.com/api/v1/stats/id 
