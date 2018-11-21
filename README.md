# ProjetDeSemestre
# ProjetDeSemestre  - Cloud Computing
Préparé par: 	**Bariza boulmerdj**
				**geurdouh wafa**

### Travail à réaliser : Développement puis déploiement d'une application de conversion de document sur Cloud.

#### Enoncé:

#### Partie 1: Architecture de l'application et modèle de données:

Pour développer notre application, nous avons choisi l'architecture MVC car elle 
offre beaucoups d'avantages. on peut citer par exemple, Une conception claire et efficace grâce 
à la séparation des données de la vue et du contrôleur

MODELE :
dèle représente les données de notre application et les règles métiers.
C'est dans ce composant que s'effectuent les traitements liés au cœur du métier.

VUE:
représente l'interface utilisateur. Elle n'effectue
aucun traitement, elle se contente simplement
d'afficher les données que lui fournit le modèle. Il
peut tout à fait y avoir plusieurs vues qui présentent
les données d'un même modèle.

Contrôleur :

Le contrôleur se charge d'intercepter les requêtes de
l'utilisateur, d'appeler le modèle puis de rediriger vers la
vue adéquate. Il ne doit faire aucun traitement. Il ne fait
que de l'interception et de la redirection.

Architecture MVC :
![basic_mvc](https://user-images.githubusercontent.com/44171439/48838724-8572dd00-ed89-11e8-8f79-fcfb05a9827c.png)







L’ Architecture de la couche de donnée:
-pour implémenter notre base de donnée on a décidé d’utiliser MYSQL .
MySQL est donc un Système de Gestion de Bases de Données Relationnelles qui utilise le langage SQL.
- Le SQL (Structured Query Language) est un langage informatique qui permet d'interagir avec des bases de données relationnelles. C'est le langage pour base de données le plus répandu, et c'est bien sûr celui utilisé par MySQL.
l’architecture de notre base de donnée est :
client : id, nom ,prenom ,email
document :  id 
serveur:id 
La maniére de gestion de demande de client:
-le client entrer dans la page d'accueil,il depose son document et choisie le type de conversion et entrer un mail de contact.
-Les composants de cette catégorie reçoivent les requêtes des clients, les traitent et les transmettent aux composants chargés de traiter les données une servlet peut jouer ce rôle et leur retourner une réponse.
-si la conversion est terminer elle envoi un lien de telechergement.
Les technologies que nous avons utilisés dans notre application sont :
1- cloud computing
2- JAVA ee
3- Serivce web 


![basic_mvc](https://user-images.githubusercontent.com/44171439/48838724-8572dd00-ed89-11e8-8f79-fcfb05a9827c.png)
