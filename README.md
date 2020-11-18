# click-travel

**Sujet** : Récupérer un billet d'avion pour aller à la destination de vos rêves

![screenshot](/assets/screenshot.png)

# Partie 1 (1h)

* Forker le repository Github du front end ( https://github.com/bratosab/click-travel)
* Récupérer les destinations depuis l'api (http://travel-api.clicksomeone.com/explorer/#/DestinationController/DestinationController.find), les stocker dans le store, faire un getter dans le store qui récupère les destinations de rêve (IsDreamDestination) et remplacer les boutons codés en dur de la home page par les destinations de rêve
* **Comiter** votre code avec le commentaire FEAT(index)

# Partie 2 (30 minute)

* Au clic sur un bouton, naviguer vers une vue correspondant à la liste des billets d'avion pour se rendre à la destination de rêve sélectionnée
* Les informations pour récupérer la liste des billets sont disponibles via l'api :
http://travel-api.clicksomeone.com/explorer/#/TicketController/TicketController.find

* Exemple de contenu du paramètre filter (avec le url Encode parcequ'on est sympa) :
exemple d'URL à appeler :
http://travel-api.clicksomeone.com/tickets?filter=%7B%0A%20%20%22offset%22%3A%200%2C%0A%20%20%22limit%22%3A%20100%2C%0A%20%20%22skip%22%3A%200%2C%0A%20%20%22where%22%3A%20%7B%0A%20%20%20%20%22to%22%3A%20%22NYC%22%0A%20%20%7D%0A%7D

* **Comiter** votre code avec le commentaire FEAT(TicketList)

# Partie 3 (1h30)

* Au clic sur un billet de la liste, affichage du billet avec le même design que le billet suivant :

![ticket](/assets/ticket-example.jpg)

Avec les champs suivant :
* le nom du passager
* Le nom du vol
* ville de départ
* ville d'arrivée
* la classe
* La porte d'embarquement
* Le siège
* le numéro du billet

**Comiter** votre code FEAT(DisplayTicket)

# Partie 4 (1 minute)
*  **Pusher** votre code sur Github
*  Envoyer le lien du repo à @Abdallah et @Gaultier

# Les liens

* Code Front : https://github.com/bratosab/click-travel

* Code API : https://github.com/bratosab/click-travel-api => a récupérer en cas de force majeur si l'API est down

* Swagger api : http://travel-api.clicksomeone.com/explorer/#/DestinationController/DestinationController.find

* Liens vers l'image docker : https://hub.docker.com/r/bratosab/click-travel-api

# infos :

le back est disponible sur internet, mais vous pouvez l'hoster chez vous si vous le souhaiter

## Vous avez jusque midi bon courage

## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).
