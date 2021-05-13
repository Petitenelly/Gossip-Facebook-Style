# README


* POUR LA PAGE D'ACCUEIL : http://localhost:3000/gossips/new



This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version
 ruby '2.7.1'
* System dependencies
 
* Configuration

* Database creation

* Database initialization

* How to run the test suite
1. Bundle install 
2. rails db:create
3. rails db:migrate 
4. rails db:seed 
5. rails s 
* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions



Ennoncé du projet :
Ça y est ! Tu commences à maîtriser les fondamentaux de Rails, les termes de MVC, routes, params et bases de données te sont familiers et tu commences à être fier des quelques applications que tu as codé cette semaine.

Aujourd'hui, nous allons un peu plus loin avec notre application Gossip Project, en rajoutant des features un peu plus stylées que tu pourras peut-être réutiliser pour l'architecture de ton projet final.

Pour commencer, tu peux reprendre ton app d'hier car la base de données reste globalement la même.

Ce projet sera peu guidé, je vais juste te donner une liste de fonctionnalités que ton app devra avoir et tu vas les implémenter. Celles-ci reprendrons essentiellement ce que tu as vu cette semaine et la semaine dernière.

Voici ce que tu vas devoir implémenter dans l'application :

Nous allons commencer par un CRUD succinct des utilisateurs : création
Nous allons mettre en place un système de login / logout avec une page de connexion
Nous allons faire en sorte que les potins créés soient associés à l'utilisateur en cours, idem pour les commentaires
Nous allons rendre impossible la création de potin si l'utilisateur n'est pas connecté. Idem pour show du potin
Édition et destruction des potins
Puis nous allons mettre en place le système de likes
