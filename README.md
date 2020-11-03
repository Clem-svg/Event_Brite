# Event Brite 2.0

![](https://images.unsplash.com/photo-1520095972714-909e91b038e5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2850&q=80)

Cette application est une version minimaliste (mais fonctionnelle, c'est le plus important) d'Eventbrite, un site qui propose plein d'événements que tu peux rejoindre. 
Les événements ne concernent qu'une seule ville, la ville où tu te trouves. Voici ce que tu peux faire :

* En arrivant sur la page d'accueil, un visiteur a accès aux événements. Un header donne un lien d'accès aux pages importantes : accueil, créer un événement, s'inscrire / se connecter, mon profil
  
* Il est possible de s'inscrire sur le site avec une adresse email

* Une personne inscrite sur le site peut proposer un événement. Il renseignera le titre, une description, une date de début, une durée, un prix
  
* Sur la page qui affiche les événements, tu verras les infos de l'événement (description, date, durée, prix, nombre de participants)
  
* Une personne connectée peut rejoindre un événement. Elle va cliquer sur un lien pour accéder à un formulaire d'inscription à un événement. Sur ce formulaire on donnera son prénom, nom, et on mettra son numéro de carte bleue pour payer l'événement
  
* Une personne qui a créé un événement peut accéder à une page qui affiche la liste des invités. À partir de cette page, ils peuvent accéder à une page pour éditer l'événement, voir avoir le bouton pour le supprimer

* Chaque utilisateur aura une page profil, avec ses informations de base (prénom, nom, description). Si un utilisateur est sur sa page profil, il a accès à deux liens : un pour éditer ses informations primordiales (email, mot de passe) avec le bouton pour supprimer son compte, l'autre pour éditer les informations de profil telles que le prénom, le nom, ou la description
  
* Actions impossibles à faire si la personne n'est pas connectée : rejoindre un événement, créer un événement, accéder à la page "mon profil"

## Lancer l'app :
$ git clone
$ bundle install
$ (yarn install --check-files) optionnel
$ rails db:create
$ rails db:migrate
$ rails db:seed
$ rails s

Tu peux maintenant lancer http://localhost:3000/ dans ton nativagteur. 

Enjoy ! ✌️