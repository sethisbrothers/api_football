
![Logo](ressources/logo.jpg)



# **RESTful API de gestion des statistiques des joueurs de foot  _avec Node.js et Express_**

Dans le cadre de la digitalisation du système de gestion des statistiques des joueurs, nous avons conçu une solution répondant aux critères de performance suivant: 

- L'API passe les test GET, POST, PUT et DELETE sur [PostMan](https://www.postman.com/)

![images](ressources/postman.png)

- Site deployé sur [Heroku](https://dashboard.heroku.com/)

![images](ressources/heroku.png)
## Technologies utilisées pour construire l'API:
- NodeJS
- Javascript
- Express - Framework Web rapide, sans opinion et minimaliste pour  Node.js


### Packages installés 
- nvm - Node version Manager 
- npm - Node Package Manager 
- Node.js
- Express installé avec npm (npm install express body-parser morgan).
## Fonctionnement de L'API

#### Route 

```http
  GET /api/v1/stats/:id
```
```http
  POST /api/v1/stats/
```
```http
  PUT /api/v1/stats/:id
```
```http
  DELETE /api/v1/stats/:id
```

| Methode | URL     | Description                |
| :-------- | :------- | :------------------------- |
| `GET` | https://sleepy-brook-74161.herokuapp.com/api/v1/stats/45 | **Créer et enregistrer les stats d'un joueur** |
| `POST` | https://sleepy-brook-74161.herokuapp.com/api/v1/stats | **Obtenir les informarions d'un joueur à partir de son identifiant** |
| `PUT` |https://sleepy-brook-74161.herokuapp.com/api/v1/stats/45 | **Mettre à jour les informations d'un joueur existant** |
| `DELETE` | https://sleepy-brook-74161.herokuapp.com/api/v1/stats/45 | **Supprimer les stats d'un joueur** |



## Signification des status

### Erreur

`404` : *Les statistiques du joueur n'existent pas*

`500` : *Erreur du serveur*

### Réussite
`201` : *Les statistiques du joueur ont été crées* 

`200` : *La requete a été exécuté avec succès*


## Authors

- [@Sethibrothers](https://www.github.com/sethisbrothers)

